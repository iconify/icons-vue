<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="n967ulefd"/><path fill="url(#SVGTLzytj4Q)" class="pq5ln1bzs"/><path fill="url(#SVGYo6L7b4Z)" class="jupa_wrdy"/><path fill="url(#SVGzCDGZd4S)" class="aqmdyzb7a"/></g><defs><linearGradient id="SVGTLzytj4Q" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="eovjo6bxs"/><stop offset=".5" class="fgrp8fbcs"/><stop offset="1" class="way122bfl"/></linearGradient><linearGradient id="SVGYo6L7b4Z" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop offset=".18" class="y_p1xgpdd"/><stop offset="1" class="x14jkoknm"/></linearGradient><linearGradient id="SVGzCDGZd4S" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="xzxw2o4tu"/><stop offset=".49" class="xbxg82u2g"/><stop offset="1" class="z0ibpjbqs"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:brn-background" /></template>
<style>
.aqmdyzb7a {
  d: path("M4 6.5L12 20l8-13.5L13.66 4l.84 1.5l3.805 1.395L12 17.67L5.695 6.9L9.5 5.5l.84-1.5z");
}

.eovjo6bxs {
  stop-color: var(--svg-color--19f1fe, #19f1fe);
}

.fgrp8fbcs {
  stop-color: var(--svg-color--7f6efb, #7f6efb);
}

.ft5dv1b6b {
  fill: none;
}

.jupa_wrdy {
  d: path("M8.5 9.835L12 4l3.5 5.835L14.84 11L12 6.24L9.16 11z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.n967ulefd {
  fill: var(--svg-color--0eebff, #0eebff);
  d: path("M7.5 13.675L6.78 12.5L4 17.24L10.5 20l-1-1.5l-3.815-1.66zm9 0l.72-1.175L20 17.24L13.5 20l1-1.5l3.815-1.66z");
}

.pq5ln1bzs {
  d: path("M10.5 11L12 8.5l1.5 2.5l-.555 1.235l.555 1.265L12 16l-1.5-2.5l.555-1.265zm1.5 4l.885-1.5l-.25-.68l-.135.18v-1.09l.32-.91L12 9.5l-.82 1.5l.32.91V13l-.135-.18l-.25.68z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.way122bfl {
  stop-color: var(--svg-color--8450fd, #8450fd);
}

.x14jkoknm {
  stop-color: var(--svg-color--1ca4fd, #1ca4fd);
}

.xbxg82u2g {
  stop-color: var(--svg-color--6d5ffe, #6d5ffe);
}

.xzxw2o4tu {
  stop-color: var(--svg-color--c63fff, #c63fff);
}

.y_p1xgpdd {
  stop-color: var(--svg-color--3636e5, #3636e5);
}

.z0ibpjbqs {
  stop-color: var(--svg-color--268ef5, #268ef5);
}

</style>
