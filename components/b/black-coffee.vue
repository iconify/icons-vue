<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rzfw-hbit"/><path class="xyfibl0wn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:black-coffee" /></template>
<style>
.rzfw-hbit {
  fill: currentColor;
  d: path("M5 9.5h10.5V16a3.5 3.5 0 0 1-3.5 3.5H8.5A3.5 3.5 0 0 1 5 16Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xyfibl0wn {
  d: path("M15.5 11H17a2.5 2.5 0 0 1 0 5h-1.5m-8-12v2.5M10.25 4v2.5M13 4v2.5");
}

</style>
