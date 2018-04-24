## Setup projects
to support decorators in jsx, do belows:
```
  npm run eject
```

remove the eslint config in config/webpack.config.dev.js

```
// First, run the linter.
// It's important to do this before Babel processes the JS.
// {
//   test: /\.(js|jsx|mjs)$/,
//   enforce: 'pre',
//   use: [
//     {
//      options: {
//        formatter: eslintFormatter,
//   eslintPath: require.resolve('eslint'),

//      },
//      loader: require.resolve('eslint-loader'),
//     },
//   ],
//   include: paths.appSrc,
// },
```
