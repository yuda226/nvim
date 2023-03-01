# NeoVim

This is a nvim repository that aims to be as easy to use as vscode.

## curl nvim setup from Bruce
cd ~/.config
git clone https://github.com/BruceChanJianLe/nvim.git
cd nvim
./isntall_neovim.bash

## install packer
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim

## generate bash_aliases for neovim
cd ~
touch .bash_aliases
- #!/usr/bin/env bash
- alias vim ='nvim'
- alias vi = 'nvim'

## setup and source
look for packer.lua 
- space pf enter lua
- :so # to source
- :PackerInstall # to install

look for telescope.lua
- space pf enter lua
- :so
- :TSUpdate

- comment out sumneko_lua at lsp.lua for ubuntu18
- &&
- download ripgrep from https://github.com/BurntSushi/ripgrep/releases
- dpkg -i ripgrep*.deb

quit vim and source .bashrc

## VimScript to Lua

Convert init.vim to init.lua [https://www.youtube.com/watch?v=BoDU6QOmEOY]
Setting Up init.lua [https://www.youtube.com/watch?v=qb6fPgZMRF4]

## Plugin Manager

For neovim version 0.5 and above (gotta install from source) use [Packer](https://github.com/wbthomason/packer.nvim) to manage your plugins.

## Reference
- [learning_video1](https://www.youtube.com/watch?v=gnupOrSEikQ)
- [learning_video2](https://www.youtube.com/watch?v=65Wq4fjREUU)
- [lua_nvim](https://www.youtube.com/watch?v=IP3J56sKtn0)
- [new_learning_video](https://www.youtube.com/watch?v=434tljD-5C8) [https://github.com/jessarcher/dotfiles]
- [vscode-ish setup](https://www.youtube.com/watch?v=GcoHnB5DoFA)

Github
- [current_ref_nvim_config](https://github.com/ChristianChiarulli/nvim/)
- [lunarvim](https://github.com/LunarVim/LunarVim)
- [vscodevim](https://github.com/josethz00/neovim-like-vscode)
- [someref](https://gist.github.com/benawad/b768f5a5bbd92c8baabd363b7e79786f)
- [luaref](https://github.com/mizlan/dots-nightly/tree/lua-port)
