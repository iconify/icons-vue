<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bz3rwcc7t"/><path class="xflgzbbhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-balloon-pair" /></template>
<style>
.bz3rwcc7t {
  d: path("M10 17c-4.5-3.25-7.5-6-7.5-9.25c0-2.5 2-4.25 4.25-4.25c1.5 0 2.75.75 3.25 1.75c.5-1 1.75-1.75 3.25-1.75c2.25 0 4.25 1.75 4.25 4.25c0 3.25-3 6-7.5 9.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xflgzbbhz {
  fill: currentColor;
  d: path("M15.5 20.5c-3-2.25-5-4.25-5-6.75c0-1.75 1.25-3.25 3-3.25c1 0 1.75.5 2 1.25c.25-.75 1-1.25 2-1.25c1.75 0 3 1.5 3 3.25c0 2.5-2 4.5-5 6.75Z");
}

</style>
