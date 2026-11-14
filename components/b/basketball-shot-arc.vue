<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eoz5drbdg"/><path class="l3sl83idz"/><path class="yqr-j6b6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basketball-shot-arc" /></template>
<style>
.eoz5drbdg {
  d: path("M6 15a6 6 0 1 0 12 0a6 6 0 1 0-12 0m0 0h12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3sl83idz {
  d: path("M7.75 10.75q4.25 4.25 0 8.5m8.5-8.5q-4.25 4.25 0 8.5");
}

.yqr-j6b6i {
  d: path("M3 11a9.5 9.5 0 0 1 18 0");
}

</style>
