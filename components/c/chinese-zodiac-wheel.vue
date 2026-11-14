<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="regd_xbnf"/><path class="yl_auqhjo"/><path class="qyt3fmp0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chinese-zodiac-wheel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qyt3fmp0m {
  d: path("M11.776 2h.448a.794.794 0 0 1 .651 1.25a1.068 1.068 0 0 1-1.75 0A.794.794 0 0 1 11.776 2");
}

.regd_xbnf {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M12 2.5v19M2.5 12h19");
}

.yl_auqhjo {
  fill: currentColor;
  d: path("M14 10V5.75A6.5 6.5 0 0 1 18.25 10Z");
}

</style>
