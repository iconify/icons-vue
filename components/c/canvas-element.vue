<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lrvoe9j9s"/><path class="k_njosbdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:canvas-element" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_njosbdf {
  fill: currentColor;
  d: path("M4 2.5zA1.5 1.5 0 0 1 5.5 4A1.5 1.5 0 0 1 4 5.5A1.5 1.5 0 0 1 2.5 4A1.5 1.5 0 0 1 4 2.5m16 0zA1.5 1.5 0 0 1 21.5 4A1.5 1.5 0 0 1 20 5.5A1.5 1.5 0 0 1 18.5 4A1.5 1.5 0 0 1 20 2.5m-16 16zA1.5 1.5 0 0 1 5.5 20A1.5 1.5 0 0 1 4 21.5A1.5 1.5 0 0 1 2.5 20A1.5 1.5 0 0 1 4 18.5m16 0za1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

.lrvoe9j9s {
  d: path("M5.75 4h12.5A1.75 1.75 0 0 1 20 5.75v12.5A1.75 1.75 0 0 1 18.25 20H5.75A1.75 1.75 0 0 1 4 18.25V5.75A1.75 1.75 0 0 1 5.75 4");
}

</style>
