# nvim
The NeoVin config for zanbinxu.


### Install NeoVim
First you should install NeoVim.
Copy this instruction to your terminal and run.

```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
./nvim.appimage
```


### Using nvim +checkhealth to check your nvim status 
```
nvim +checkhealth
```

If there are errors, you should upgrade or install your programs. 
Before that you make sure that your computer alread install pip.
If install pip error to run get-pip.py please upgrade your python3 version.
Let me show you.


### Install pip
Download pip and run python get-pip.py.
```
wget https://bootstrap.pypa.io/get-pip.py --no-check-certificate
```
```
python get-pip.py
```


### Completion nvim status
We using instruction to solve nvim errors.
To install it:
```
pip2 install neovim && \
pip3 install neovim 
```
To update it:
```
pip2 install neovim --upgrade && \
pip3 install neovim --upgrade
```

Run :checkhealth again, everything should be ok now.
Now you have Neovim installed with Python provider support enabled.


### Install plug manager
[junegunn/vim-plug](https://github.com/junegunn/vim-plug#unix-linux) is a very popular minimalistic plugin manager.
Copy this instruction to your terminal and run.
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```


### Install plug
Plug are in the init.vim, instruction :PlugInstall is be ok.

### Plug usage
#### Vista
Commands
Command	Description
Vista	Open/Close vista window for viewing tags or LSP symbols
Vista!	Close vista view window if already opened
Vista!!	Toggle vista view window
:Vista [EXECUTIVE]: open vista window powered by EXECUTIVE.

:Vista finder [EXECUTIVE]: search tags/symbols generated from EXECUTIVE.

See :help vista-commands for more information.











