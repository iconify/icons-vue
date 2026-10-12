<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x14fbvbjf"/><path class="czse88b_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:email-ai" /></template>
<style>
.czse88b_t {
  d: path("m3.5 8.75l6.25 4.5L16 8.75m2.25-6q.36 2.64 3 3q-2.64.36-3 3q-.36-2.64-3-3q2.64-.36 3-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x14fbvbjf {
  width: 14px;
  height: 11.25px;
  x: 2.75px;
  y: 8px;
  rx: 2.25px;
}

</style>
