<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ttc5rcb-u"/><path class="mzsye2bux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blush" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mzsye2bux {
  d: path("M5.5 15a3.5 3.5 0 0 1 7 0");
}

.ttc5rcb-u {
  d: path("M2.5 14.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m15-6l-2.25-5q3.25-1.5 6.5 0l-2.25 5Zm1 0v13");
}

</style>
