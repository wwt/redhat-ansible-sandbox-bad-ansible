## Overview

[Inspired by Tony Kay's bad-ansible](https://github.com/tonykay/bad-ansible)

Bad Ansible is a deliberately poorly constructed ansible project designed to give students a basic project to cleanup, refactor, and improve. It represents a newcomer's, aka _newbie_, approach to hacking together a functional playbook to deploy a three tier app.

The entry point, `main.yml` contains multiple _good enough_ plays, and some redundant ones.

The short of it is:

* if it is not needed -- remove it
* if there is a better way to do it -- implement it

This repo is meant to be used with the WWT Red Hat Ansible Sandbox Lab on the [WWT Platform](http://wwt.com)