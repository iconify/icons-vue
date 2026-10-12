<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e2h22crbt"/><path class="w-wwzbctp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cardigan" /></template>
<style>
.e2h22crbt {
  d: path("M9.75 4.5h4.5q1.25 0 2.35.58l2.05 1.09q1.1.58 1.25 1.82l1.2 9.77q.15 1.24-1.07 1.5l-1.06.23q-1.22.26-2.47.26h-9q-1.25 0-2.47-.26l-1.06-.23Q2.75 19 2.9 17.76l1.2-9.77q.15-1.24 1.25-1.82L7.4 5.08q1.1-.58 2.35-.58");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-wwzbctp {
  d: path("M9.25 4.75L12 13.5v6.25m2.75-15L12 13.5m-6.5 3.75v2.25m3.25-2.25v2.5m6.5-2.5v2.5m3.25-2.5v2.25");
}

</style>
