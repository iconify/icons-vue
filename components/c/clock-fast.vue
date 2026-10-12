<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xqztkowql"/><path class="r-f11_wvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clock-fast" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r-f11_wvo {
  d: path("M14 8.25V12l2.5 1.5m-13.75-5h2.5M2.75 12H4.5m-1.75 3.5h2.5");
}

.xqztkowql {
  cx: 14px;
  cy: 12px;
  r: 7.25px;
}

</style>
