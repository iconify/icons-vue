<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="m24ul_b7n"/><path class="bwwu6bc3g"/><path clip-rule="evenodd" class="xcyxhtd5x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lqty-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bwwu6bc3g {
  fill: var(--svg-color--1542cd, #1542cd);
  d: path("M10.822 18.78c-6.81 0-9.498-8.877-3.483-12.618c-.715 7.419 3.09 7.583 6.622 7.419c5.918-.275 5.922 5.198 5.922 5.198z");
}

.ft5dv1b6b {
  fill: none;
}

.m24ul_b7n {
  fill: var(--svg-color--2eb6ea, #2eb6ea);
  d: path("M10.788 18.788a6.788 6.788 0 1 0 0-13.576a6.788 6.788 0 0 0 0 13.576");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xcyxhtd5x {
  fill: var(--svg-color--745ddf, #745ddf);
  fill-rule: evenodd;
  d: path("M17.216 14.184c-1.03 2.635-3.444 4.517-6.428 4.6q.105.004.212.004h9s-.12-3.23-2.784-4.604");
}

</style>
