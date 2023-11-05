# stack-templates

> Modern templates for the Haskell Tool Stack

![Status](https://img.shields.io/badge/status-active-success.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/wwmoraes/stack-templates/master.svg)](https://results.pre-commit.ci/latest/github/wwmoraes/stack-templates/master)

[![GitHub Issues](https://img.shields.io/github/issues/wwmoraes/stack-templates.svg)](https://github.com/wwmoraes/stack-templates/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/wwmoraes/stack-templates.svg)](https://github.com/wwmoraes/stack-templates/pulls)

---

## 📝 Table of Contents

- [About](#-about)
- [Usage](#-usage)
- [TODO](./TODO.md)
- [Contributing](./CONTRIBUTING.md)

## 🧐 About

Templates to create new Haskell projects using Stack with the minimal set of
configurations and boilerplate I need.

## 🎈 Usage

You can use any templates here directly with stack:

```shell
stack new PROJECT_NAME wwmoraes/default
```

Replace `default` with any other `*.hsfiles` in this repository as needed.

You can optionally configure stack to use one of the templates from here through
the [`default-template`][stack-default-template] setting.

[stack-default-template]: https://docs.haskellstack.org/en/stable/yaml_configuration/#default-template
