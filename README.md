# webpack-mentor
🚩 tell the truth about webpack
+ [official docs](https://webpack.js.org/)
+ [great book](https://survivejs.com/webpack/)
+ [links](https://github.com/webpack-contrib/awesome-webpack)


## Motivation
+ scripts loading in order nightmare
+ dependencies managment by turning everything into a module
  + js
  + css
  + images
  + svgs
+ different import styles
  + making deps explicit
  + no global nightmare

## Basics Ideas
+ loader (text mapper)
  + babel
  + posctcss
  + url-loader
  + file-loader
+ chains of loaders
+ plugins - optimization & stuff
  + commonsChunkPlugin
  + prefetchPlugin
  + lodash
  + gzip
  + PrefetchPlugin
  + Service Workers
  + ExtractText
  + S3
  + Dedupe
  + HTML5

## Super Features
+ tree-shaking
+ code splitting
+ hashing (long term caching)
+ chunking
+ service worker
