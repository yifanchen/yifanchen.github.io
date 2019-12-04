## Personal blog built on Jekyll

### Todos of the site:

- [] Rewrite `gulp.js` to support Node LTS
- [] Rewrite `gulp.js` to be more efficient in dev mode
- [] Google Alaytics and GTM
- [] Nav Logtics
- [x] Following PR of Faraday_middleware issuse
- [] Maybe move the footer to the bottom on Mobile Devices
- [] Re-commit `package-lock.json` once vulnerability issues are fixed

### Currently supported node version:

    tested: v8.2.1
    testing queue: <10.0.0

`package-lock.json` caused some vulnerability issues, removing it temporarily.

### Install

I completely forgot the dependencies of the site, had to have a friend reminding me how to install. I'd better start to doc everything toady, it has been a good lesson.

    ruby -v
    gem install bundler
    bundle
    npm i
    npm i -g gulp-cli


### Issues when running bundler:

    While executing gem ... (Errno::EPERM)
    Operation not permitted - /usr/bin/bundle

    sudo gem install bundler -n /usr/local/bin

### Custom domain

Github page now supports custom domain with HTTPS, don't forget to add or udpate the CNAME next time.