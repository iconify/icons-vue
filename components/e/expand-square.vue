<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="k0zqeccla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:expand-square" /></template>
<style>
.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.k0zqeccla {
  d: path("m14 10l3.5-3.5m-3 0h3v3M10 10L6.5 6.5m3 0h-3v3M10 14l-3.5 3.5m0-3v3h3M14 14l3.5 3.5m0-3v3h-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
