# Drupal-7-css-and-gulp-theme-by-mutasem-elayyoub
Drupal 7 with Gulp ++ NODE.JS ++ AutoPrefixer  startup theme by Mutasem Elayyoub

This theme built for people who prefer CSS and they still want to use Gulp with their theme.

How to use:

1- clone the theme from https://github.com/whywebs/Drupal-7-css-and-gulp-theme-by-mutasem-elayyoub for free by 

cd ~/sites/YOUR-WEBSITE/sites/all/themes/
git clone https://github.com/whywebs/Drupal-7-css-and-gulp-theme-by-mutasem-elayyoub whywebs2016
cd whywebs2016
//rebuild you site by ' gulp build '
// Watch your changes by ' gulp watch '
//Check your gulp within your theme ' gulp '

Now all your files will be inside your build folder e.g css files are inside build/css , javascript files are inside build/scripts ...etc

so the extensions that been used within this theme


event-stream@3.3.2 node_modules/event-stream
├── stream-combiner@0.0.4
├── duplexer@0.1.1
├── from@0.1.3
├── pause-stream@0.0.11
├── map-stream@0.1.0
├── split@0.3.3
└── through@2.3.8

gulp-load-plugins@0.8.1 node_modules/gulp-load-plugins
├── multimatch@2.0.0 (array-differ@1.0.0, array-union@1.0.1, minimatch@2.0.10)
└── findup-sync@0.2.1 (glob@4.3.5)

del@1.2.1 node_modules/del
├── is-path-cwd@1.0.0
├── object-assign@3.0.0
├── each-async@1.1.1 (set-immediate-shim@1.0.1, onetime@1.1.0)
├── is-path-in-cwd@1.0.0 (is-path-inside@1.0.0)
├── globby@2.1.0 (array-union@1.0.1, async@1.5.2, glob@5.0.15)
└── rimraf@2.5.2 (glob@7.0.3)

gulp-filter@2.0.2 node_modules/gulp-filter
├── merge-stream@0.1.8
├── multimatch@2.1.0 (array-differ@1.0.0, arrify@1.0.1, array-union@1.0.1, minimatch@3.0.0)
├── through2@0.6.5 (xtend@4.0.1, readable-stream@1.0.34)
├── plexer@0.0.3 (readable-stream@1.1.14)
└── gulp-util@3.0.7 (array-differ@1.0.0, beeper@1.1.0, object-assign@3.0.0, lodash._reescape@3.0.0, lodash._reinterpolate@3.0.0, lodash._reevaluate@3.0.0, array-uniq@1.0.2, fancy-log@1.2.0, has-gulplog@0.1.0, gulplog@1.0.0, chalk@1.1.3, lodash.template@3.6.2, replace-ext@0.0.1, vinyl@0.5.3, minimist@1.2.0, multipipe@0.1.2, dateformat@1.0.12, through2@2.0.1)

gulp-size@1.3.0 node_modules/gulp-size
├── chalk@1.1.3 (escape-string-regexp@1.0.5, supports-color@2.0.0, ansi-styles@2.2.1, has-ansi@2.0.0, strip-ansi@3.0.1)
├── through2@2.0.1 (xtend@4.0.1, readable-stream@2.0.6)
├── gulp-util@3.0.7 (array-differ@1.0.0, beeper@1.1.0, object-assign@3.0.0, lodash._reinterpolate@3.0.0, lodash._reescape@3.0.0, lodash._reevaluate@3.0.0, array-uniq@1.0.2, fancy-log@1.2.0, has-gulplog@0.1.0, replace-ext@0.0.1, gulplog@1.0.0, lodash.template@3.6.2, minimist@1.2.0, vinyl@0.5.3, multipipe@0.1.2, dateformat@1.0.12)
├── gzip-size@1.0.0 (browserify-zlib@0.1.4, concat-stream@1.5.1)
└── pretty-bytes@2.0.1 (number-is-nan@1.0.0, get-stdin@4.0.1, meow@3.7.0)

gulp-cache@0.2.10 node_modules/gulp-cache
├── try-json-parse@0.1.1
├── object-assign@3.0.0
├── object.omit@1.1.0 (isobject@1.0.2, for-own@0.1.4)
├── object.pick@1.1.2 (isobject@2.1.0)
├── vinyl@0.5.3 (clone-stats@0.0.1, replace-ext@0.0.1, clone@1.0.2)
├── cache-swap@0.2.3 (object-assign@4.1.0, graceful-fs@4.1.4, mkdirp@0.5.1, rimraf@2.5.2)
├── bluebird@2.10.2
├── through2@0.6.5 (xtend@4.0.1, readable-stream@1.0.34)
└── gulp-util@3.0.7 (array-differ@1.0.0, beeper@1.1.0, array-uniq@1.0.2, lodash._reinterpolate@3.0.0, lodash._reevaluate@3.0.0, lodash._reescape@3.0.0, fancy-log@1.2.0, has-gulplog@0.1.0, gulplog@1.0.0, lodash.template@3.6.2, chalk@1.1.3, replace-ext@0.0.1, multipipe@0.1.2, minimist@1.2.0, dateformat@1.0.12, through2@2.0.1)

gulp-concat@2.6.0 node_modules/gulp-concat
├── through2@0.6.5 (xtend@4.0.1, readable-stream@1.0.34)
├── concat-with-sourcemaps@1.0.4 (source-map@0.5.6)
└── gulp-util@3.0.7 (array-differ@1.0.0, beeper@1.1.0, array-uniq@1.0.2, object-assign@3.0.0, lodash._reevaluate@3.0.0, lodash._reinterpolate@3.0.0, lodash._reescape@3.0.0, fancy-log@1.2.0, has-gulplog@0.1.0, replace-ext@0.0.1, gulplog@1.0.0, lodash.template@3.6.2, chalk@1.1.3, minimist@1.2.0, multipipe@0.1.2, vinyl@0.5.3, dateformat@1.0.12, through2@2.0.1)

gulp-postcss@4.0.3 node_modules/gulp-postcss
├── vinyl-sourcemaps-apply@0.1.4 (source-map@0.1.43)
├── postcss@4.1.16 (js-base64@2.1.9, source-map@0.4.4, es6-promise@2.3.0)
├── through2@0.6.5 (readable-stream@1.0.34, xtend@4.0.1)
└── gulp-util@3.0.7 (array-differ@1.0.0, beeper@1.1.0, array-uniq@1.0.2, lodash._reescape@3.0.0, lodash._reinterpolate@3.0.0, lodash._reevaluate@3.0.0, object-assign@3.0.0, replace-ext@0.0.1, fancy-log@1.2.0, has-gulplog@0.1.0, gulplog@1.0.0, lodash.template@3.6.2, chalk@1.1.3, minimist@1.2.0, vinyl@0.5.3, multipipe@0.1.2, dateformat@1.0.12, through2@2.0.1)

gulp-sourcemaps@1.6.0 node_modules/gulp-sourcemaps
├── graceful-fs@4.1.4
├── strip-bom@2.0.0 (is-utf8@0.2.1)
├── convert-source-map@1.2.0
├── vinyl@1.1.1 (clone-stats@0.0.1, replace-ext@0.0.1, clone@1.0.2)
└── through2@2.0.1 (xtend@4.0.1, readable-stream@2.0.6)

gulp-shell@0.2.11 node_modules/gulp-shell
├── async@0.9.2
├── lodash@2.4.2
├── through2@0.6.5 (xtend@4.0.1, readable-stream@1.0.34)
└── gulp-util@3.0.7 (array-differ@1.0.0, beeper@1.1.0, array-uniq@1.0.2, lodash._reinterpolate@3.0.0, lodash._reevaluate@3.0.0, lodash._reescape@3.0.0, object-assign@3.0.0, has-gulplog@0.1.0, fancy-log@1.2.0, gulplog@1.0.0, lodash.template@3.6.2, replace-ext@0.0.1, chalk@1.1.3, multipipe@0.1.2, vinyl@0.5.3, dateformat@1.0.12, minimist@1.2.0, through2@2.0.1)

gulp@3.9.1 node_modules/gulp
├── interpret@1.0.1
├── pretty-hrtime@1.0.2
├── deprecated@0.0.1
├── archy@1.0.0
├── tildify@1.2.0 (os-homedir@1.0.1)
├── v8flags@2.0.11 (user-home@1.1.1)
├── minimist@1.2.0
├── chalk@1.1.3 (escape-string-regexp@1.0.5, supports-color@2.0.0, ansi-styles@2.2.1, has-ansi@2.0.0, strip-ansi@3.0.1)
├── semver@4.3.6
├── orchestrator@0.3.7 (stream-consume@0.1.0, sequencify@0.0.7, end-of-stream@0.1.5)
├── liftoff@2.2.1 (extend@2.0.1, rechoir@0.6.2, flagged-respawn@0.3.2, resolve@1.1.7, findup-sync@0.3.0)
├── vinyl-fs@0.3.14 (graceful-fs@3.0.8, strip-bom@1.0.0, vinyl@0.4.6, defaults@1.0.3, mkdirp@0.5.1, glob-stream@3.1.18, glob-watcher@0.0.6, through2@0.6.5)
└── gulp-util@3.0.7 (array-differ@1.0.0, beeper@1.1.0, array-uniq@1.0.2, object-assign@3.0.0, lodash._reescape@3.0.0, lodash._reevaluate@3.0.0, lodash._reinterpolate@3.0.0, fancy-log@1.2.0, has-gulplog@0.1.0, gulplog@1.0.0, lodash.template@3.6.2, replace-ext@0.0.1, vinyl@0.5.3, multipipe@0.1.2, dateformat@1.0.12, through2@2.0.1)

autoprefixer-core@5.2.1 node_modules/autoprefixer-core
├── num2fraction@1.2.2
├── browserslist@0.4.0
├── postcss@4.1.16 (js-base64@2.1.9, source-map@0.4.4, es6-promise@2.3.0)
└── caniuse-db@1.0.30000479

browser-sync@2.13.0 node_modules/browser-sync
├── server-destroy@1.0.1
├── emitter-steward@1.0.0
├── dev-ip@1.0.1
├── opn@3.0.3 (object-assign@4.1.0)
├── qs@6.2.0
├── http-proxy@1.13.3 (eventemitter3@1.2.0, requires-port@1.0.0)
├── browser-sync-client@2.4.2 (fresh@0.3.0, etag@1.7.0)
├── ua-parser-js@0.7.10
├── resp-modifier@6.0.1 (debug@2.2.0, minimatch@2.0.10)
├── portscanner@1.0.0 (async@0.1.15)
├── connect@3.4.1 (utils-merge@1.0.0, parseurl@1.3.1, debug@2.2.0, finalhandler@0.4.1)
├── eazy-logger@3.0.2 (tfunk@3.0.2)
├── micromatch@2.3.8 (filename-regex@2.0.0, array-unique@0.2.1, is-extglob@1.0.0, normalize-path@2.0.1, extglob@0.3.2, is-glob@2.0.1, arr-diff@2.0.0, regex-cache@0.4.3, expand-brackets@0.1.5, kind-of@3.0.3, object.omit@2.0.0, parse-glob@3.0.4, braces@1.8.5)
├── immutable@3.8.1
├── serve-static@1.10.3 (escape-html@1.0.3, parseurl@1.3.1, send@0.13.2)
├── serve-index@1.7.3 (escape-html@1.0.3, parseurl@1.3.1, batch@0.5.3, debug@2.2.0, accepts@1.2.13, mime-types@2.1.11, http-errors@1.3.1)
├── fs-extra@0.26.7 (path-is-absolute@1.0.0, klaw@1.3.0, jsonfile@2.3.1, rimraf@2.5.2, graceful-fs@4.1.4)
├── socket.io@1.4.6 (has-binary@0.1.7, debug@2.2.0, socket.io-parser@2.2.6, engine.io@1.6.9, socket.io-adapter@0.4.0, socket.io-client@1.4.6)
├── bs-recipes@1.2.2
├── chokidar@1.5.1 (path-is-absolute@1.0.0, glob-parent@2.0.0, async-each@1.0.0, is-glob@2.0.1, is-binary-path@1.0.1, anymatch@1.3.0, inherits@2.0.1, readdirp@2.0.0)
├── yargs@4.7.1 (decamelize@1.2.0, camelcase@3.0.0, set-blocking@1.0.0, y18n@3.2.1, window-size@0.2.0, require-main-filename@1.0.1, lodash.assign@4.0.9, yargs-parser@2.4.0, os-locale@1.4.0, cliui@3.2.0, string-width@1.0.1, pkg-conf@1.1.3, read-pkg-up@1.0.1)
├── easy-extender@2.3.2 (lodash@3.10.1)
├── localtunnel@1.8.1 (openurl@1.1.0, debug@2.2.0, yargs@3.29.0, request@2.65.0)
├── rx@4.1.0
└── browser-sync-ui@0.6.0 (async-each-series@0.1.1, connect-history-api-fallback@1.2.0, stream-throttle@0.1.3, weinre@2.0.0-pre-I0Z7U9OV)

gulp-imagemin@2.4.0 node_modules/gulp-imagemin
├── object-assign@4.1.0
├── plur@2.1.2 (irregular-plurals@1.2.0)
├── chalk@1.1.3 (escape-string-regexp@1.0.5, supports-color@2.0.0, ansi-styles@2.2.1, strip-ansi@3.0.1, has-ansi@2.0.0)
├── pretty-bytes@2.0.1 (number-is-nan@1.0.0, get-stdin@4.0.1, meow@3.7.0)
├── through2-concurrent@1.1.1 (through2@2.0.1)
├── gulp-util@3.0.7 (array-differ@1.0.0, beeper@1.1.0, lodash._reevaluate@3.0.0, lodash._reescape@3.0.0, lodash._reinterpolate@3.0.0, array-uniq@1.0.2, has-gulplog@0.1.0, fancy-log@1.2.0, object-assign@3.0.0, gulplog@1.0.0, lodash.template@3.6.2, replace-ext@0.0.1, vinyl@0.5.3, multipipe@0.1.2, through2@2.0.1, dateformat@1.0.12, minimist@1.2.0)
└── imagemin@4.0.0 (optional@0.1.3, stream-combiner2@1.1.1, buffer-to-vinyl@1.1.0, readable-stream@2.1.4, concat-stream@1.5.1, imagemin-svgo@4.2.1, vinyl-fs@2.4.3, imagemin-jpegtran@4.3.2, imagemin-optipng@4.3.0, imagemin-gifsicle@4.2.0)

gulp-sass@1.3.3 node_modules/gulp-sass
├── clone@0.1.19
├── map-stream@0.1.0
├── vinyl-sourcemaps-apply@0.1.4 (source-map@0.1.43)
├── gulp-util@3.0.7 (array-differ@1.0.0, beeper@1.1.0, object-assign@3.0.0, array-uniq@1.0.2, lodash._reevaluate@3.0.0, lodash._reescape@3.0.0, lodash._reinterpolate@3.0.0, has-gulplog@0.1.0, fancy-log@1.2.0, replace-ext@0.0.1, chalk@1.1.3, gulplog@1.0.0, lodash.template@3.6.2, vinyl@0.5.3, multipipe@0.1.2, dateformat@1.0.12, minimist@1.2.0, through2@2.0.1)
└── node-sass@2.1.1 (get-stdin@4.0.1, object-assign@2.1.1, replace-ext@0.0.1, cross-spawn@0.2.9, shelljs@0.3.0, semver@4.3.6, chalk@0.5.1, mkdirp@0.5.1, npmconf@2.1.2, meow@3.7.0, gaze@0.5.2, nan@1.9.0, sass-graph@1.3.0, request@2.72.0, mocha@2.5.3, pangyp@2.3.3)

Please if you like this make sure to leave me a comment, and if you didn't like it please comment too because i need to fix this theme and keep this theme the easiest for any developer


Regards
Mutasem Elayyoub(Sam)
Sam@whywebs.com
www.whywebs.com
