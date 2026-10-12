<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="h1nvq6bbq"/><path class="k4doyybfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drawing-compass-sharp" /></template>
<style>
.h1nvq6bbq {
  cx: 12px;
  cy: 5.75px;
  r: 2.25px;
}

.k4doyybfm {
  d: path("M10.75 7.75L5.75 21m7.5-13.25l5 13.25m-11.5-5.5c3.25 1.75 7.25 1.75 10.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
