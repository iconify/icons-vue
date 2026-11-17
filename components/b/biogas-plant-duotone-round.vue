<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pzy4o9bvq"/><path class="m4dwvac-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:biogas-plant-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m4dwvac-e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12v7a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-7a6.1 6.1 0 0 0-12 0m0 0h12M9.27 7.006A6.1 6.1 0 0 1 21 8m-8.653 0H21m0 0v7a2 2 0 0 1-2 2h-4");
}

.pzy4o9bvq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 19v-7a6.1 6.1 0 0 1 12 0v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2");
}

</style>
