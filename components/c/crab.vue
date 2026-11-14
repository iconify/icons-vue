<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uo4yqp8cx"/><path class="azby3_bwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crab" /></template>
<style>
.azby3_bwo {
  d: path("m7.5 11.5l-2-3c-2-.5-3-3-1.5-5L5.5 6L7 4c1.25 1.25 1 3.25-1.5 4.5m11 3l2-3c2-.5 3-3 1.5-5L18.5 6L17 4c-1.25 1.25-1 3.25 1.5 4.5M5.75 14L3 13m3 3.5l-3 1m5 1l-2 2M18.25 14L21 13m-3 3.5l3 1m-5 1l2 2M10 13h.01M14 13h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uo4yqp8cx {
  d: path("M5.5 14.5a6.5 4.5 0 1 0 13 0a6.5 4.5 0 1 0-13 0");
}

</style>
