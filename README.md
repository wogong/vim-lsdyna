#vim-lsdyna
[VIM](http://www.vim.org/) filetype plugin for [Ls-Dyna](http://www.lstc.com) FE solver.

What is Ls-Dyna filetype plugin?

It's just bunch of VIM scripts to speed up work with Ls-Dyna keyword file.

##Main features
- Syntax highlighting
- Folding
- Keyword library
- Useful commands, functions and mappings

###Syntax highlighting
With color syntax it's easier to navigate through a keyword file.

![vimLsDynaColorSyntax](https://raw.github.com/wiki/gradzikb/vim-lsdyna/screenshots/vimLsDynaColorSyntax.gif)

###Folding
Node & element table folding, no more never ending scrolling!

![vimLsDynaFold](https://raw.github.com/wiki/gradzikb/vim-lsdyna/screenshots/vimLsDynaFold.gif)

###Keyword library
With keyword library you can very quick add a new Ls-Dyna keyword into your model.

![vimLsDynaKeyLib](https://raw.github.com/wiki/gradzikb/vim-lsdyna/screenshots/vimLsDynaKeyLib.gif)

###Curve commands
You can use commands to operate with curve data directly in VIM.

![vimLsDynaScale](https://raw.github.com/wiki/gradzikb/vim-lsdyna/screenshots/vimLsDynaScale.gif)

###Commands, functions & mappings
The plugin has couple of great functions to make your work even faster:
- mappings
- comment/uncomment
- data line autoformating
- keyword text objects
- include path

##Installation

[Pathogen](https://github.com/tpope/vim-pathogen)

```
cd ~/.vim/bundle
git clone https://github.com/gradzikb/vim-lsdyna
```

##Documentation

List of all great features and detail information about them you will find in plugin documentation

`:help lsdyna`

##License

The GNU General Public License

Copyright &copy; 2014 Bartosz Gradzik
