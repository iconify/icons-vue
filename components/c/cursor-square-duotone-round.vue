<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eftjkbcmd"/><path class="afmmmhbmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-square-duotone-round" /></template>
<style>
.afmmmhbmu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5a2 2 0 1 1 4 0a2 2 0 0 1-4 0m7 5l11 4l-5 2l-2 5z");
}

.eftjkbcmd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.236 3.832A3 3 0 1 1 7.763 6.17a3 3 0 0 1-5.527-2.338m19.106 9.228a1.002 1.002 0 0 1 .029 1.868l-4.602 1.841l-1.841 4.602a1 1 0 0 1-1.868-.029l-4-11a1 1 0 0 1 1.282-1.282Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
