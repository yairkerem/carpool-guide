# מדריך הסעות להורים

The onboarding guide for parents joining a [Carpool](https://github.com/yairkerem/Carpool)
group, at **https://yairkerem.github.io/carpool-guide/**

It lives in its own repository on purpose. The app is served from
`yairkerem.github.io/Carpool/` and its manifest claims that whole path as its
scope, so anything hosted beside it can be captured two ways: an installed
Android app opens in-app any link under its scope, and the app's service worker
answers navigations within it. A guide sent to a parent has to open as a page,
on any phone, whether or not that phone already has the app — so it is hosted
outside the scope entirely, where neither can reach it.

One file, no build step. Edit `index.html` and push.
