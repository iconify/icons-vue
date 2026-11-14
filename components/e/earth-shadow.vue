<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nlmwa6bpu"/><path class="oiqxm-y6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:earth-shadow" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nlmwa6bpu {
  d: path("M3 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.oiqxm-y6u {
  d: path("M11.25 7.25L20 12l-8.75 4.75M8.5 6.5v11");
}

</style>
