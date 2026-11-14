<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yuq-jrx4t"/><path class="qzgidsb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-thinking" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qzgidsb1y {
  d: path("M7.75 12.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m3.5 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m3.5 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

.yuq-jrx4t {
  d: path("M7 18.5a4 4 0 0 1 0-8a5.5 5.5 0 0 1 11 1a3.5 3.5 0 0 1-1 7Z");
}

</style>
