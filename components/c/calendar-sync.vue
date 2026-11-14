<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xv_y5yg6a"/><path class="vcixxsyhk"/><path class="oqaetq4do"/><path class="ntvv1oabo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:calendar-sync" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ntvv1oabo {
  d: path("m8.25 16.5l1.25-1.25l1.25 1.25");
}

.oqaetq4do {
  d: path("m13.25 14l1.25 1.25L15.75 14m-1.585 2.5A2.5 2.5 0 0 1 9.5 15.25");
}

.vcixxsyhk {
  d: path("M9.835 14a2.5 2.5 0 0 1 4.665 1.25");
}

.xv_y5yg6a {
  d: path("M7 5h10a3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 17V8.5A3.5 3.5 0 0 1 7 5m1-2v4m8-4v4M3.5 10h17");
}

</style>
