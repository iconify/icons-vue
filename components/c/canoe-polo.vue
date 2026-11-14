<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wv6dgxber"/><path class="r2eszj_qo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:canoe-polo" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r2eszj_qo {
  d: path("M14 5q3 2.5 6 0");
}

.wv6dgxber {
  d: path("M2.5 12C5 14 8 14.5 12 14.5s7-.5 9.5-2.5c-1 5-4.5 7.5-9.5 7.5S3.5 17 2.5 12m11-5.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
