<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cm4wxdbtx"/><path class="m5_p7dbbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:art-insurance" /></template>
<style>
.cm4wxdbtx {
  d: path("M3 9.25a9 6.75 0 0 1 18 0a3.5 3.5 0 0 0-6 0a3.5 3.5 0 0 0-6 0a3.5 3.5 0 0 0-6 0M7.625 12h8.75A2.625 2.625 0 0 1 19 14.625v4.25a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 18.875v-4.25A2.625 2.625 0 0 1 7.625 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m5_p7dbbg {
  d: path("M7.75 18.75L11 15l2.5 2.75l1.25-1.25l1.5 1.5");
}

</style>
