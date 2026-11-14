<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xppz9ovei"/><path class="h0-c0rbhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charity-concert" /></template>
<style>
.h0-c0rbhz {
  d: path("M4.25 9.5a5.75 5.75 0 0 0 11.5 0M10 15.25v6.25m-3.5 0h5.9m2.35-2a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3.5 0v-5m0 0L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xppz9ovei {
  d: path("M10 2.5za3 3 0 0 1 3 3v3a3 3 0 0 1-3 3a3 3 0 0 1-3-3v-3a3 3 0 0 1 3-3");
}

</style>
