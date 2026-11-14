<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zmv0hdcdc"/><path class="xk23ufb0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:black-swan" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xk23ufb0m {
  d: path("M17 14.5c0-3.5-3.75-4.5-3.75-8c0-2.25 1.25-3.5 3-3.5c1.5 0 2.5 1 2.75 2.5l1.75 2.25M7 16.5c1.5 0 2.5.5 3.5.5c1.25 0 2.25-.5 3.5-.5");
}

.zmv0hdcdc {
  d: path("M2.5 11.5c1.5 2 4 3 7 3H17c1.5 0 2.75-1.25 3.5-3c0 4.5-3 7.5-7.5 7.5H9c-4 0-6.5-3-6.5-7.5");
}

</style>
