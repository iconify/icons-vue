<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r5omwrbxv"/><path class="o2g_kjb4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hole-in-one" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o2g_kjb4h {
  d: path("M5 17a5 5 0 0 1 10 0m2.5-14v11.5m1.75-10.375za1.337 1.337 0 0 1 0 2.25a1.136 1.136 0 0 1-1.75-.955v-.34a1.136 1.136 0 0 1 1.75-.955");
}

.r5omwrbxv {
  d: path("M2.5 17a9 3.5 0 1 0 18 0a9 3.5 0 1 0-18 0");
}

</style>
