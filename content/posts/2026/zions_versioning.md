+++
date = '2026-07-16T22:39:25+01:00'
draft = false
title = "Zion's Versioning"
tags = ["dev"]
+++

## Introduction

I never quite got how semantic versioning worked. So the other day I though of making a blog post of my versioning system which, in my opinion is simpler and clearer than [semantic versioning](https://semver.org).

## Versioning

The way Zion's Versioning works is simple:  
`feature.patch`

The `feature` increments every new feature and the `patch` increments after a bug fix or feature the maintainer/developer forgot to add/fix.

## Refactors Edition

Now of course I had to make something that could compete with semantic versioning. So that is what Refactors Edition is for. The format is:  
`refactor.feature.patch`

Each refactor is a new version of the codebase, ideally written from scratch.

## Betas, Alphas and Prototypes

Now any good software developer would know that good applications aren't just releases. That is what Betas and Alphas are for.

**Betas**  
`1.13.0-b1`  
Indicates the 1st beta for the `1.13.0` release.

**Alphas**  
`1.13.0-a2`  
Indicates the 2nd alpha for the `1.13.0` release.
