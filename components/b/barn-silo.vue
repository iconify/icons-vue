<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6-0qgb4b"/><path class="ve8zqkbsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barn-silo" /></template>
<style>
.f6-0qgb4b {
  d: path("m3.193 13.408l1.811-3.22a1.5 1.5 0 0 1 .706-.639l2.919-1.277a1.5 1.5 0 0 1 1.235.015l2.699 1.259a1.5 1.5 0 0 1 .673.624l1.821 3.238a1.5 1.5 0 0 1 .193.735v5.107a1.5 1.5 0 0 1-1.5 1.5H4.5a1.5 1.5 0 0 1-1.5-1.5v-5.107a1.5 1.5 0 0 1 .193-.735M17 21V7a2.25 2.25 0 0 1 4.5 0v14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ve8zqkbsj {
  d: path("M7.75 15.5h1.5a1.5 1.5 0 0 1 1.5 1.5v2.5a1.5 1.5 0 0 1-1.5 1.5h-1.5a1.5 1.5 0 0 1-1.5-1.5V17a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
