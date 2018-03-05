# mkreact-component

> React component configuration script

### Purpose
Much of the busy work associated with building web components, is setting up a
consistent working environments with the bells and whistles just the way we want.

This script basically insures I get what I am I expecting each time I build
a React component. Additionally it provides some features to speed up publishing
to npmjs.org registry.

```sh
$ cd /my/main/component/folder
$ mkreact-component --project=MyComponent --open

$ cd ./MyComponent

$ mkreact-component --publish --bump=patch
 - or -
$ mkreact-component --publish=patch

```
# Open in Atom
I choose to edit bash using Atom. So, the `--open` flag targets Atom as the editor.
If it suits your needs, change that up or use the `EDITOR` variable.

# Install

```sh

# or wherever you put your shell scripts
cd ~/bin

$ git clone https://github.com/xybersolve/mkreact-component.git
 - or -
$ git clone git@github.com:xybersolve/mkreact-component.git

```
Include it in your PATH, so that it is available, wherever you are creating
your component.

# Contributing
Issues and Pull requests are always welcome. Please keep in mind that there is a code of conduct.

# [Code of Conduct](CODE_OF_CONDUCT.md)

# [License](LICENSE.md)
