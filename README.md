# MesloNerdFont-in-chrome-OS

This repository show how to use Meslo Nerd Font in chrome OS terminal.

If you want to use lunarvim or starship ... on your chromebook, you are supposed to use Nerd Font to correctly display icon&emoji.

tested on chrome 118.0.0.0

1. open your terminal
2. press`CTRL+SHIFT+J`
3. copy&run

```javascript
term_.prefs_.set('font-family', 'MesloLGM Nerd Font');
term_.prefs_.set('user-css-text', '@font-face {font-family: "MesloLGM Nerd Font"; src: url("https://raw.githubusercontent.com/ye-rm/MesloNerdFont-in-chrome-OS/main/MesloLGMNerdFont-Regular.ttf"); font-weight: normal; font-style: normal;}')
```

![image-20231115131624887](https://typora-markdown-2003.obs.cn-north-4.myhuaweicloud.com/image-20231115131624887.png)

Now the terminal can display icon&emoji

![image-20231115131343510](https://typora-markdown-2003.obs.cn-north-4.myhuaweicloud.com/image-20231115131343510.png)

## How to use other Nerd Fonts?

1. download your preferred fonts.
2. upload it on a repository.(like this repo)
3. edit 👇🏻

```javascript
term_.prefs_.set('font-family', '<replace by font-family-name>');
term_.prefs_.set('user-css-text', '@font-face {font-family: "<replace by font=family-name>"; src: url("replace by font url"); font-weight: normal; font-style: normal;}')
```

 for example:

![image-20231115133020747](https://typora-markdown-2003.obs.cn-north-4.myhuaweicloud.com/image-20231115133020747.png)

replace 'github.com' with 'raw.githubusercontent.com' in https://github.com/ye-rm/MesloNerdFont-in-chrome-OS/blob/main/MesloLGMNerdFont-Regular.ttf then you got the font url.

To test the font url whether correct, you can paste it in your browser, then the font file can be downloaded.

## How to config Nerd Font in visual studio code(vscode) on chromebook.

To be done..
