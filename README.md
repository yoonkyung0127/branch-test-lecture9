# Lecture 9: Remote Branch and Collaboration

This repository demonstrates the Lecture 9 workflow: branch, collaborate through a remote repository, fetch changes, resolve a merge conflict, and merge the result.

## Files

- `collaboration.txt` shows the final text after resolving a feature-versus-hotfix conflict.
- `workflow.md` lists the remote Git commands.
- `.gitignore` excludes common local secrets and machine-specific files.

## Branch history

The `feature/lecture9-update` branch changes the same status line as an urgent correction on `main`. Their changes are merged after resolving the conflict. Inspect the history with `git log --oneline --graph --all`.
