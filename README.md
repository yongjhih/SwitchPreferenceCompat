SwitchPreferenceCompat
======================

[![Build Status](https://travis-ci.org/yongjhih/SwitchPreferenceCompat.png?branch=master)](https://travis-ci.org/yongjhih/SwitchPreferenceCompat) [![Stories in Ready](https://badge.waffle.io/yongjhih/SwitchPreferenceCompat.png)](http://waffle.io/yongjhih/SwitchPreferenceCompat) 
[![Bountysource](https://www.bountysource.com/badge/team?team_id=43965&style=bounties_posted)](https://www.bountysource.com/teams/8tory/bounties?utm_source=8tory&utm_medium=shield&utm_campaign=bounties_posted)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.infstory/switch-preference-compat/badge.svg?style=flat)](https://maven-badges.herokuapp.com/maven-central/com.infstory/switch-preference-compat)
[ ![Download](https://api.bintray.com/packages/yongjhih/maven/com.infstory%3Aswitch-preference-compat/images/download.svg) ](https://bintray.com/yongjhih/maven/com.infstory%3Aswitch-preference-compat/_latestVersion)

Allow easy to use [SwitchCompat](https://developer.android.com/reference/android/support/v7/widget/SwitchCompat.html) as preference.

![SwitchPreferenceCompat](app/Screenshot.png "SwitchPreferenceCompat")

Usage
=====

```xml
<CheckBox
    android:key="example_checkbox"
    android:title="@string/pref_title_example"
    android:summary="@string/pref_description_example"
    android:defaultValue="true" />
```

to

```xml
<com.cgollner.unclouded.preferences.SwitchPreferenceCompat
    android:key="example_checkbox"
    android:title="@string/pref_title_example"
    android:summary="@string/pref_description_example"
    android:defaultValue="true" />
```
Installation
============

build.gradle:

```gradle
dependencies {
    compile 'com.infstory:switch-preference-compat:1.0.+'
}
```

Requirement
===========

* Theme.AppCompat

build.gradle:

```gradle
dependencies {
    compile 'com.android.support:appcompat-v7:21.+'
}
```

Credit
======

* @ChristianGollner

This SwitchPreferenceCompat is imported from https://plus.google.com/+ChristianGollner/posts/badausxo1J6

* Preference class: https://gist.github.com/cgollner/5b31123c98b2c1cad8dc
* Layout resource: https://gist.github.com/cgollner/3c7fe2f9d34aee38bd0c
