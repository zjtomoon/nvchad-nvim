# nvchad官网

  [NvChad](https://nvchad.github.io/)
  [Nvchad-github](https://github.com/NvChad/NvChad)

# 初始安装
```bash 
  git clone https://gitcode.net/mirrors/NvChad/NvChad ~/.config/nvim --depth 1
  nvim +'hi NormalFloat guibg=#1e222a' +PackerSync
```
# 配置packer.nvim的国内镜像

+ 找到~/.config/nvim/lua/plugins/packerInit.lua ，在git = {}中添加`default_url_format = "https://hub.fastgit.org/%s"`


