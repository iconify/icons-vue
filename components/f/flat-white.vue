<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x_z33vbzn"/><path class="tiyl4eb5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flat-white" /></template>
<style>
.tiyl4eb5q {
  d: path("M17 7.25h1a2.25 2.25 0 0 1 0 4.5h-1.75M3 16.5q9 3 18 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x_z33vbzn {
  d: path("M4 6h13v3a5 5 0 0 1-5 5H9a5 5 0 0 1-5-5Z");
}

</style>
