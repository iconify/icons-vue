<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pw74nhfev"/><path class="hugpugg-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arcade-cabinet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hugpugg-c {
  d: path("M10 5.5h4A1.5 1.5 0 0 1 15.5 7v2a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 9V7A1.5 1.5 0 0 1 10 5.5m-2.5 13V17m5.5 1.5h.01m2.99 0h.01");
}

.pw74nhfev {
  d: path("M7.75 2.5h8.5A1.75 1.75 0 0 1 18 4.25v8.136a1.75 1.75 0 0 0 .383 1.093l1.234 1.542A1.75 1.75 0 0 1 20 16.114v3.636a1.75 1.75 0 0 1-1.75 1.75H5.75A1.75 1.75 0 0 1 4 19.75v-3.636a1.75 1.75 0 0 1 .383-1.093l1.234-1.542A1.75 1.75 0 0 0 6 12.386V4.25A1.75 1.75 0 0 1 7.75 2.5");
}

</style>
