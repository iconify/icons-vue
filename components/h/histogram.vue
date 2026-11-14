<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8u760b4u"/><path class="m-v1fvmyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:histogram" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-v1fvmyk {
  d: path("M7.5 14zA1.5 1.5 0 0 1 9 15.5V19a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 6 19v-3.5A1.5 1.5 0 0 1 7.5 14m3-5za1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 9 19v-8.5A1.5 1.5 0 0 1 10.5 9m3-3.5zA1.5 1.5 0 0 1 15 7v12a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 12 19V7a1.5 1.5 0 0 1 1.5-1.5m3 6.5za1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 15 19v-5.5a1.5 1.5 0 0 1 1.5-1.5");
}

.p8u760b4u {
  d: path("M3.5 3v17.5H21");
}

</style>
