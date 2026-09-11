# Contributing

Contributions are welcome.

## Pull Requests

Please submit your changes through a pull request.

Before opening a pull request:

* Keep your changes focused and relevant.
* Prefer linking the pull request to one or more related issues.
* Clearly describe what the pull request changes and why.
* Update documentation or tests when necessary.

For bug fixes, new features, or significant changes, it is recommended to create or reference an issue first.

You can link issues using GitHub keywords such as:

`Closes #123`

or:

`Fixes #123, #456`

## Commit Messages

Commit messages should follow the [Conventional Commits](https://www.conventionalcommits.org/) specification.

Examples:

* `feat: add user profile page`
* `fix: handle empty API response`
* `docs: update installation guide`
* `refactor: simplify authentication logic`
* `test: add coverage for login flow`
* `chore: update dependencies`

Use a scope when it helps clarify the affected area:

`feat(auth): add OAuth login`

Breaking changes should be marked according to the Conventional Commits specification.

## Review and CI

A pull request must not be merged until:

* All required CI checks have passed.
* All required reviews have been approved.
* Requested changes have been resolved.
* There are no unresolved merge conflicts.

If new commits are pushed after approval, additional review may be required.

## Merging

Pull requests should only be merged after they satisfy all repository protection rules and review requirements.

Maintainers may request additional changes before merging when necessary.
