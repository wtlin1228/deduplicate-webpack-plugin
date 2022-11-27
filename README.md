# deduplicate-webpack-plugin

## Usage

```js
import DeduplicateWebpackPlugin from "deduplicate-webpack-plugin";

// webpack config
const config = {
  // ...

  plugins: [
    // ...

    new DeduplicateWebpackPlugin({
      cacheDir,
      rootPath,
      packageManager: "yarn", // or npm
    }),

    // ...
  ],

  // ...
};
```

## TODO

- [] Can we get resolver from nmf directly?
- [] Add tests
