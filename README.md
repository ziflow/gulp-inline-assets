# @ziflow/gulp-inline-assets
> Inline local and external assets (images, fonts) in a CSS file in the form of a data URI.

## Install
```shell
$ npm install --save-dev @ziflow/gulp-inline-assets
```

## Usage

```js
```

```javascript
var gulp = require('gulp');
var inlineAssets = require('@ziflow/gulp-inline-assets');

gulp.task('default', function () {
    return gulp.src('src/app.css')
        .pipe(inlineAssets(options))
        .pipe(gulp.dest('dist'));
});
```

## Options

### ignoreErrors
Type: `boolean`

Determines if URLs with errors should be ignored.

## License
MIT @ Gustavo Henke
