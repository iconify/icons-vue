<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="apkpivb4q"/><path class="bn6p61bue"/><path class="prxbd-bqg"/><path class="qcbhw8bsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cash-denominations" /></template>
<style>
.apkpivb4q {
  d: path("M14.125 13.5h4.75a2.625 2.625 0 0 1 2.625 2.625v.75a2.625 2.625 0 0 1-2.625 2.625h-4.75a2.625 2.625 0 0 1-2.625-2.625v-.75a2.625 2.625 0 0 1 2.625-2.625");
}

.bn6p61bue {
  d: path("M11.5 15h-4A1.5 1.5 0 0 1 6 13.5v-4A1.5 1.5 0 0 1 7.5 8H16a1.5 1.5 0 0 1 1.5 1.5v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.prxbd-bqg {
  d: path("M6 10H4a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 4 3h10a1.5 1.5 0 0 1 1.5 1.5V8m-1 8.5a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0M8 11.25a1.75 1 0 1 0 3.5 0a1.75 1 0 1 0-3.5 0");
}

.qcbhw8bsc {
  d: path("M7 5.5a1.75 1 0 1 0 3.5 0a1.75 1 0 1 0-3.5 0");
}

</style>
