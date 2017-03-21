# vamr-presentation

## Perquisites
1. nodenv

## Install version of node dependant on .node-version

```
nodenv install $(cat .node-version)
```

## Install revealjs-md

```
nodenv exec npm i -g revealjs-md
nodenv rehash
```

## building static site

```
nodenv exec reveal-md slides.md --theme slides --static docs
```

FYI, any new assets or ammendents to theme needs copied into docs, need to automate this.
