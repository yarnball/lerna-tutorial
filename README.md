# Lerna tutorial

## TLDR;

* `npm install` (installs lerna)
* `lerna bootstrap` (connects all the packages)
* `node ./packages/connector run start` (console logs "alpha" and "beta" from combind use example module)

* Tree Structure

* `packages`
  * `alpha` (`deps: []`)
  * `beta` (`deps: []`)
  * `connector` (`deps: ["alpha", "beta"]`)