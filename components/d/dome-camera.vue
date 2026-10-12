<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="us1syobgb"/><circle class="ugkzx-t0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dome-camera" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ugkzx-t0u {
  cx: 13px;
  cy: 12.75px;
  r: 2px;
}

.us1syobgb {
  d: path("M2.75 5.25h18.5M3 8.25h18a9 9 0 0 1-18 0");
}

</style>
