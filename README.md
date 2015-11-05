# webpack plugin to generate map.json

## examples

```js
plugins: [
  ...,
  require('map-json-webpack-plugin')({
    // output file path, relative to process.cwd()
    output: 'dist/map.json'
  })
]
```
