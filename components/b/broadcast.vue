<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="h_tsn8bxt"/><path class="syvnecc_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:broadcast" /></template>
<style>
.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.syvnecc_m {
  d: path("M8.1 8.1a5.5 5.5 0 0 0 0 7.8m7.8-7.8a5.5 5.5 0 0 1 0 7.8M5.64 5.64a9 9 0 0 0 0 12.72M18.36 5.64a9 9 0 0 1 0 12.72");
}

</style>
