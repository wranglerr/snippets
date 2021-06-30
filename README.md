# snippets


## Installation

You can clone this by git into any path that on the `runtimepath` for vim.
```
git clone git@github.com:wranglerr/snippets.git ~/.config/nvim/snippets
```

Or you can use `vim-plugged` and add the following to your `.vimrc` file.
```
Plug 'wranglerr/snippets'
```

Here's the configuration options I have set in my `~/config/.nvim/init.vim` file.

```
let g:UltiSnipsJumpForwardTrigger="<c-b>"
let g:UltiSnipsJumpBackwardTrigger="<c-z>"
let g:ultisnips_python_style="google"
let g:UltiSnipsSnippetDirectories=["UltiSnips", "mysnippets"]
```
