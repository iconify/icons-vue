<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h_-wm4boj"/><path class="tukq70bzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bus-bike-rack" /></template>
<style>
.h_-wm4boj {
  d: path("M6.2 16H3.5V2.5h17V16h-2.7");
}

.tukq70bzt {
  d: path("M6.25 5.25h11.5v4.5H6.25Zm.75 7.5h.01m9.99 0h.01M6.5 18.3v1.2m11-1.2v1.2m-8.5-3a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
