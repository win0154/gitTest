# gitTest
Git branches are an integral part of your everyday workflow.
The following content will expend on the internal Git branching architecture.

A branch represents an independent line of development.
Branches serve as an abstraction for the edit/stage/commit process.
You can think of them as a way to request a brand new working directory, staging area,
and project history.
New commits are recorded in the history for the current branch,
which results in a fork in the history of the project.

The git branch command lets you create, list, rename, and delete branches.
It doesn't let you switch between branches or put a forked history back together agin.
For this reason, git branch is tightly integrated with the 'git checkout' and 'git merge' commands.
