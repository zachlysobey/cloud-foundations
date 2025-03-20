# Changelog

## 2025-03-20

### Scaffolding this thing out

#### commit: `initial commit`

```console
git init
git add README.md
git commit -m "initial commit"
git branch -M master
git remote add origin git@github.com:zachlysobey/cloud-foundations.git
git push -u origin master
```

Following that, I created this file (`CHANGELOG.md`) and updated the `README.md`,
amending those changes into my initial commit, and *force pushing*.

#### commit: `chore(ci): Github Actions hello world`

This commit creates a minimal "Hello World" Github Actions workflow.

#### commit: `chore(deps): integrate dependabot`

This commit configures *Dependabot* such that it should let us know when there are newly available versions in the Github Actions setup.
