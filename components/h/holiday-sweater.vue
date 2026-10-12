<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yv7c09fyu"/><path class="nk1wq05rf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:holiday-sweater" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nk1wq05rf {
  d: path("M9.25 3.5a2.75 2.25 0 0 0 5.5 0M8 18v2.75M12 18v2.75M16 18v2.75");
}

.yv7c09fyu {
  d: path("M9.75 3.25h4.5q1.25 0 2.35.58l2.05 1.09q1.1.58 1.23 1.82l1.24 12.02q.13 1.24-1.09 1.5l-1.06.23q-1.22.26-2.47.26h-9q-1.25 0-2.47-.26l-1.06-.23q-1.22-.26-1.09-1.5L4.12 6.74q.13-1.24 1.23-1.82L7.4 3.83q1.1-.58 2.35-.58");
}

</style>
