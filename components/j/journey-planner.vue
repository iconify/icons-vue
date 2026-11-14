<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qbko7sbel"/><path class="po1ak1l0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:journey-planner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.po1ak1l0u {
  d: path("M15.5 15s-3-2.5-3-4.5a3 3 0 0 1 6 0c0 2-3 4.5-3 4.5m-9 1h.01m2.74 0l2.5-.5");
}

.qbko7sbel {
  d: path("m3.636 4.716l4.526-1.132a1.5 1.5 0 0 1 .678-.011l6.32 1.354a1.5 1.5 0 0 0 .678-.011l3.798-.95A1.5 1.5 0 0 1 21.5 5.421v12.408a1.5 1.5 0 0 1-1.136 1.455l-4.526 1.132a1.5 1.5 0 0 1-.678.011l-6.32-1.354a1.5 1.5 0 0 0-.678.011l-3.798.95A1.5 1.5 0 0 1 2.5 18.579V6.171a1.5 1.5 0 0 1 1.136-1.455");
}

</style>
