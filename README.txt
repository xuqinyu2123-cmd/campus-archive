CAMPUS//ARCHIVE V6.1 VIDEO FIX

修复：
1. 结果主人格图片改为内嵌数据源，不再依赖 assets 路径，解决 GitHub Pages 主图空白。
2. 部署包仍附 16 张 2048×2048 lossless WebP 人格图。
3. 答题主区新增动态像素场景条与 3 组 HUD，消除录屏中大面积空白。
4. 结果首屏新增六维速览，减少右侧留白。
5. Service Worker 改为导航 network-first，并自动删除旧缓存。
