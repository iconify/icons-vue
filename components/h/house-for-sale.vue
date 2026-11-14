<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w-4nlzq4k"/><path class="rswa1_mlw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-for-sale" /></template>
<style>
.rswa1_mlw {
  d: path("M14.25 12.75C14 11.9 13.15 11.5 12 11.5c-1.4 0-2.25.7-2.25 1.75c0 2.1 4.5 1.2 4.5 4c0 1-.95 1.75-2.25 1.75c-1.2 0-2.05-.5-2.25-1.25M12 10v1.5m0 7.5v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-4nlzq4k {
  d: path("M3 10.5L12 3l9 7.5V21H3Z");
}

</style>
