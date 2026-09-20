<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="n3pvjc7av"/><path class="jtqimmbsb"/><path class="l5t1ldbur"/><path class="tl1bvrbqi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lake-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.jtqimmbsb {
  fill: var(--svg-color--1f1f1f, #1f1f1f);
  d: path("M4 4h16v16H4z");
}

.l5t1ldbur {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.857 14.857v1.428a4.285 4.285 0 1 0 0-8.571v1.428A2.844 2.844 0 0 1 11.715 12a2.844 2.844 0 0 1-2.858 2.857");
}

.n3pvjc7av {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 4H4v16h16z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tl1bvrbqi {
  fill: var(--svg-color--bdbec0, #bdbec0);
  d: path("M13.143 12h-1.428A4.293 4.293 0 0 0 16 16.286v-1.429A2.847 2.847 0 0 1 13.144 12");
}

</style>
