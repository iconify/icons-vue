<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="an8in5bao"/><path class="paivv5b1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-curve-down-sharp" /></template>
<style>
.an8in5bao {
  d: path("M3.75 4.75c8 0 13.25 4.75 13.25 14.5");
}

.paivv5b1d {
  d: path("m13 15.25l4 4l4-4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
