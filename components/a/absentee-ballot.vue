<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pb1isx67n"/><path class="h9d5l8btt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:absentee-ballot" /></template>
<style>
.h9d5l8btt {
  d: path("m7 3l5 3.5L17 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pb1isx67n {
  d: path("M8 12.5H5.5a2 2 0 0 0-2 2v5a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2v-5a2 2 0 0 0-2-2H16m-7.25-10h6.5A1.75 1.75 0 0 1 17 4.25v3.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 7.75v-3.5A1.75 1.75 0 0 1 8.75 2.5");
}

</style>
