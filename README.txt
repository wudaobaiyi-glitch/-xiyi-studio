========================================
 西艺设计 · XiYi Studio · 网站文件
========================================

【文件结构】
  index.html       主页（直接双击打开）
  pages/           册子的30页JPG图片
  README.txt       本说明文件

【本地预览方法】
  方法1：把整个文件夹放在桌面，双击 index.html 用浏览器打开
  方法2：在文件夹内打开终端，运行：
         python3 -m http.server 8000
         然后浏览器访问 http://localhost:8000

【上线部署方法】
  把 index.html 和 pages 文件夹一起上传到任意支持
  静态网站托管的服务，例如：
  - Vercel  (vercel.com)        免费 推荐
  - Netlify (netlify.com)        免费 推荐
  - GitHub Pages
  - 阿里云 OSS / 腾讯云 COS / 七牛云
  - 任何虚拟主机的根目录

【生成扫码二维码】
  上传后拿到网址（如 https://xiyi.vercel.app）
  在任意二维码生成器输入网址即可生成印刷用二维码

【后续修改】
  替换 pages/ 里的某张 jpg 即可更新对应页内容
  index.html 里有详细注释方便定位每个区块

