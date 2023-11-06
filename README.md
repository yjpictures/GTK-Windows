# GTK for Windows  (GitHub Actions)

[![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/yjpictures/GTK-Windows/test.yml?logo=github&label=test)
](https://github.com/yjpictures/GTK-Windows)
[![GitHub Latest Release](https://img.shields.io/github/v/release/yjpictures/GTK-Windows)](https://github.com/yjpictures/GTK-Windows/releases/latest)
[![GitHub License](https://img.shields.io/github/license/yjpictures/GTK-Windows)
](https://github.com/yjpictures/GTK-Windows/blob/master/LICENSE)


This GitHub Action will allow you to add GTK in the runner environment. This actions checks out `2022-01-04` release from [GTK+ for Windows Runtime Environment](https://github.com/tschoonj/GTK-for-Windows-Runtime-Environment-Installer) by Tom Schoonjans and adds to the runner environment.




## Usage

### Normal usage

``` yaml
- name: Add GTK to the Runner Environment
  uses: yjpictures/GTK-Windows@v1
```

### Use a custom release tag

``` yaml
- name: Add GTK to the Runner Environment
  uses: yjpictures/GTK-Windows@v1
  with:
    # The release tag to use. Default is 2022-01-04.
    release: ''
```