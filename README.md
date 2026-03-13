# vtk-builds

Automatic builds of [VTK](https://vtk.org) built with Qt using [github actions](https://github.com/features/actions), for architectures below:

|        SO           |   Arch    |
| :-----------------: | :-------: |
|  windows-latest     |  x86_64   |
|  ubuntu-2204        |  x86_64   |

## Why do I need this?

### Stand-alone distributable packages

First, you can find the static libraries among the [released files](https://github.com/xaprier/vtk-builds-qt/releases), so you can produce CI/CD pipelines to automagically build standalone packages.

## Some examples

[XAimAssist](https://github.com/xaprier/XAimAssist/blob/main/.github/workflows/release.yml)
