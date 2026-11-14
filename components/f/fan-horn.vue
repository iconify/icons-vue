<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ch0nxbbkg"/><path class="qrzpb0wzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fan-horn" /></template>
<style>
.ch0nxbbkg {
  d: path("M5 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0M2.5 21.5c0-3.75 3-6.25 6.5-6.25s6.5 2.5 6.5 6.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qrzpb0wzr {
  d: path("m12.5 9.75l9-4.25V14Z");
}

</style>
