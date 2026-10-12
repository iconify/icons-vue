<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="mhqj2bofm"/><path class="tee-gabhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:latency-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mhqj2bofm {
  cx: 10.75px;
  cy: 14px;
  r: 7.25px;
}

.tee-gabhu {
  d: path("M10.75 14V9.75M8.5 3.25H13m-2.25 0v3.5m7.5-4q.36 2.64 3 3q-2.64.36-3 3q-.36-2.64-3-3q2.64-.36 3-3");
}

</style>
