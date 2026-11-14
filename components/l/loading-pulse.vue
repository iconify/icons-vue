<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="da_ekqhmv"/><path class="llv4qgaxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loading-pulse" /></template>
<style>
.da_ekqhmv {
  fill: currentColor;
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.llv4qgaxq {
  d: path("M14.907 4.013a8.5 8.5 0 0 1 0 15.974m-5.814 0a8.5 8.5 0 0 1 0-15.974");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
