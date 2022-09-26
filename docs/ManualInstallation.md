---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Eterno-Rest 2000 (REST)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Eterno-Rest 2000 (REST)

[Home](./index.md)

Tragic disasters happen in the world of rocketry now and then, give your highest achieving Kerbals the burial they deserve with this pressurized coffin! For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `EternoRest2000` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/EternoRest2000`
* Extract the package's `EternoRest2000/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/EternoRest2000` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/EternoRest2000`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/EternoRest2000`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/EternoRest2000`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [EternoRest2000]
      + [Agencies]
        ...
      + [Compatibility]
        ...
      + [Config]
        ...
      + [Contracts]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      + [Plugins]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * changelog.md
      * GPL-2.0.txt
        ManualInstallation.htm
      * readme.htm
      * EternoRest2000.version
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none
