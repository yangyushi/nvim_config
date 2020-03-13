# nvim_config

- configuration for [neovim](https://github.com/neovim/neovim) and vim
- use [vim-plug](https://github.com/junegunn/vim-plug) for plugin management
- use [lucius](https://github.com/jonathanfilip/vim-lucius) color scheme
- mainly for python programming

## Where to Put Files

Contents in this repository should be put in 

- `~/.config/nvim` if you are using neovim
- `~/.vim` if you are using vim
- make soft link of `init.vim` as `~/.vimrc` for ubuntu 18.04

## Install Plugins

1. `:PlugInstall`
2. A new folder named `plugged` will be created

## Auto Completion

- see [YouCompleteMe](https://github.com/Valloric/YouCompleteMe)
- goto `plugged` folder
- `./install.py -all`
