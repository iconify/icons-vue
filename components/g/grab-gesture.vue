<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="msjx54bzl"/><path class="yp_o9fi9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grab-gesture" /></template>
<style>
.msjx54bzl {
  d: path("M5.25 6.5a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 3.5 0v7c0 4-2.5 6.5-6.5 6.5h-1c-4 0-6.5-2.5-6.5-6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yp_o9fi9d {
  d: path("M5.25 11h7a1.75 1.75 0 0 1 0 3.5h-3.5m0-8v1.75m3.5-1.75v1.75m3.5-1.75v1.75");
}

</style>
