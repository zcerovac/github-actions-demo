## QuickStart - GitHub Actions

GitHub offers us help with Store Code, Collaborative work, Automation.
### 1. What are GitHub Actions? 
Workflow automation service. Two main area of automation process is **Continuous Integration** and **Continuous Delivery** (CI/CD).
This means automate process of code testing, building, deployment. \
Continuous Integration is all about integrating new code, automatically test, build and merge it into existing code.
Continuous Delivery is all about publishing new version of new app, package...

*Workflows* 
- Attached to a GitHub repos
- Contain one or more **Jobs**
- Triggered upon **Events**

*Jobs*
- Define **Runner** - execution environment
- Contain one or more **Steps**
- Run in parallel (default) or sequential
- Can be conditional

*Steps*
- Execute **shell scripts** or an **Action**
- Can use custom or third party
- Can be conditional
- Can be conditional

### 3. What are Events? 

docs -> [Triggering a workflow](https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/triggering-a-workflow) \
Event can be Repository related 
  - pull_request (opened, closed, accepted)
  - push
  - fork
  - create (branch,) 

OR other
  - workflow_dispatch (manually starting the workflow)
  - schedule 

### 4. What are runners? 
### 5. What are actions?
A custom group of command that is frequently used.  \
Example: Checkout the code from the Git Repo \
```run: actions/checkout@v3``` \
docs -> [actions/checkout](https://github.com/actions/checkout)
