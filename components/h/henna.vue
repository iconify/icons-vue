<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xdo0xnzyq"/><path class="nsyitm-4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:henna" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nsyitm-4p {
  d: path("M10.5 17.5q.5-4.5 6-4.5q-.5 4.5-6 4.5");
}

.xdo0xnzyq {
  d: path("M7.5 12.25v-5.5a1.5 1.5 0 0 1 3 0v-2a1.5 1.5 0 0 1 3 0v1a1.5 1.5 0 0 1 3 0V7.5a1.5 1.5 0 0 1 3 0v7.75c0 3.5-2.5 5.5-6 5.5H12c-2.5 0-4-1.5-5.25-3.5L4 12.75A1.5 1.5 0 0 1 6.5 11zm3-5.5v3.5m3-4.5v4.5m3-2.75v2.75");
}

</style>
