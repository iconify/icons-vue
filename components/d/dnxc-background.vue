<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="i2ami1b-s"/><path class="n_zsw6bel"/><path fill="url(#SVG8ypbybbS)" class="wi-ax00mw"/><path class="aanx-srur"/><path class="lt7qxwbsq"/></g><defs><linearGradient id="SVG8ypbybbS" x1="6.978" x2="23.471" y1="6.775" y2="25.716" gradientUnits="userSpaceOnUse"><stop class="iec-__bqf"/><stop offset="1" class="p1we3jffn"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dnxc-background" /></template>
<style>
.aanx-srur {
  fill: var(--svg-color--6c6c6c, #6c6c6c);
  d: path("M15.733 9.865v1.067H16.8V9.865z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.i2ami1b-s {
  fill: var(--svg-color--e97e00, #e97e00);
  d: path("M4 20h11.733v-1.067H16.8v-1.066h1.067V16.8h1.066v-1.067H20V8.267h-1.067V7.2h-1.066V6.133H16.8V5.067h-1.067V4H8.267v1.067H7.2v1.066H6.133V7.2H5.067v1.067H4z");
}

.iec-__bqf {
  stop-color: var(--svg-color--1a1e21, #1a1e21);
}

.lt7qxwbsq {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 7.733V8.8h1.067V7.733z");
}

.n_zsw6bel {
  fill: var(--svg-color--fc0, #fc0);
  d: path("M5.066 18.932h9.6v-1.066h1.067v-1.067H16.8v-1.067h1.066v-1.066h1.067V9.332h-1.067V8.266H16.8V7.199h-1.067V6.132h-1.067V5.066H9.333v1.066H8.266V7.2H7.2v1.067H6.133v1.066H5.066z");
}

.p1we3jffn {
  stop-color: var(--svg-color--06060a, #06060a);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wi-ax00mw {
  d: path("M4 20v-3.697h1.056v-2.17H5.6v-1.067h1.067v-2.133h1.066V8.266H8.8V7.2h1.067V6.133H13.6v1.066h1.067v1.067H16.8v1.067h1.067v2.666H15.2v-1.066h-2.133v1.066h1.066v1.067H15.2v1.067h1.067v1.066h-3.2v-1.066H12v-1.067h-1.067v1.067H9.867v1.6H12v1.066h1.067v1.067h-2.134V16.8H8.8V20z");
}

</style>
