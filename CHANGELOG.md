# Changelog

> **Tags:**
> - [New Feature]
> - [Bug Fix]
> - [Breaking Change]
> - [Documentation]
> - [Internal]
> - [Polish]
> - [Experimental]

**Note**: Gaps between patch versions are faulty/broken releases.
**Note**: A feature tagged as Experimental is in a high state of flux, you're at risk of it changing without notice.

## 0.2.4

- **New Feature**
  - IO monad (@gcanti)
  - upgrade to flow v0.36, fix #45 (@gcanti)
  - add MonadError (@gcanti)
  - add Const (@gcanti)
- **Polish**
  - remove experimental React file (@gcanti)
  - cache projection in `Arr.ap` (@gcanti)
  - fix errors when experimental.const_params=true (@gcanti)
  - ignore lib folder while flow-checking (@gcanti)

## 0.2.3

- **New Feature**
  - `Foldable`: add default `foldMap` implementation (@gcanti)
  - `ChainRec` (@gcanti)
  - `Yoneda` (@gcanti)

## 0.2.2

- **New Feature**
  - add `Pointed` and `Copointed` type classes, fix #15 (@gcanti)
  - expose `concat` APIs, fix #33 (@gcanti)

## 0.2.1

- **New Feature**
  - increase the type arity of `compose` and `pipe` (@mwalkerwells)

## 0.2.0

- **Breaking Change**
  - `Traversable` now based on `traverse` instead of `sequence`, fix #26 (@gcanti)
- **New Feature**
  - `Task` (@gcanti)

## 0.1.0

Initial release
