<img src="https://cdn.rawgit.com/oh-my-fish/oh-my-fish/e4f1c2e0219a17e2c748b824004c8d0b38055c16/docs/logo.svg" align="left" width="144px" height="144px"/>

#### yarn

> A plugin for [Oh My Fish][omf-link].

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE)
[![Fish Shell Version](https://img.shields.io/badge/fish-v2.2.0-007EC7.svg?style=flat-square)](https://fishshell.com)
[![Oh My Fish Framework](https://img.shields.io/badge/Oh%20My%20Fish-Framework-007EC7.svg?style=flat-square)](https://www.github.com/oh-my-fish/oh-my-fish)

<br/>

A plugin for [yarn](https://yarnpkg.com/en/) based on [oh-my-zsh's yarn plugin](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/yarn). It includes a set of shortcuts and abbreviations that makes using yarn faster.

## Install

```fish
$ omf install yarn
```

## Abbreviations

| Abbreviation | Command                                   | Description                                                 |
| ------------ | ----------------------------------------- | ----------------------------------------------------------- |
| y            | `yarn`                                    | The Yarn command                                            |
| ya           | `yarn add`                                | Install a package in dependencies (`package.json`)          |
| yad          | `yarn add --dev`                          | Install a package in devDependencies (`package.json`)       |
| yap          | `yarn add --peer`                         | Install a package in peerDependencies (`package.json`)      |
| yb           | `yarn build`                              | Run the build script defined in `package.json`              |
| ycc          | `yarn cache clean`                        | Clean yarn's global cache of packages                       |
| yd           | `yarn dev`                                | Run the dev script defined in `package.json`                |
| yga          | `yarn global add`                         | Install packages globally on your operating system          |
| ygls         | `yarn global list`                        | Lists global installed packages                             |
| ygrm         | `yarn global remove`                      | Remove global installed packages from your OS               |
| ygu          | `yarn global upgrade`                     | Upgrade packages installed globally to their latest version |
| yh           | `yarn help`                               | Show help for a yarn command                                |
| yi           | `yarn init`                               | Interactively creates or updates a package.json file        |
| yin          | `yarn install`                            | Install dependencies defined in `package.json`              |
| yls          | `yarn list`                               | List installed packages                                     |
| yout         | `yarn outdated`                           | Check for outdated package dependencies                     |
| yp           | `yarn pack`                               | Create a compressed gzip archive of package dependencies    |
| yrm          | `yarn remove`                             | Remove installed packages                                   |
| yrun         | `yarn run`                                | Run a defined package script                                |
| ys           | `yarn serve`                              | Start the dev server                                        |
| yst          | `yarn start`                              | Run the start script defined in `package.json`              |
| yt           | `yarn test`                               | Run the test script defined in `package.json`               |
| ytc          | `yarn test --coverage`                    | Run the test script defined in `package.json` with coverage |
| yuc          | `yarn global upgrade && yarn cache clean` | Upgrade global packages and clean yarn's global cache       |
| yui          | `yarn upgrade-interactive`                | Prompt for which outdated packages to upgrade               |
| yup          | `yarn upgrade`                            | Upgrade packages to their latest version                    |
| yv           | `yarn version`                            | Update the version of your package                          |
| yw           | `yarn workspace`                          | Run a command within a single workspace.                    |
| yws          | `yarn workspaces`                         | Run a command within all defined workspaces.                |

# License

[MIT][mit] © [zephraph][author] et [al][contributors]

[mit]: https://opensource.org/licenses/MIT
[author]: https://github.com/zephraph
[contributors]: https://github.com/zephraph/plugin-yarn/graphs/contributors
[omf-link]: https://www.github.com/oh-my-fish/oh-my-fish
[license-badge]: https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
