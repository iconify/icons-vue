<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hlabr2b0y"/><path class="bmd4x5wfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:base-building" /></template>
<style>
.bmd4x5wfl {
  d: path("M10.5 16v-3.5h3V16");
}

.hlabr2b0y {
  d: path("M7.5 16V9.5L12 4l4.5 5.5V16m-14 0h19v4.5h-19Zm5 0v4.5m9-4.5v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
