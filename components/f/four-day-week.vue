<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jffa7dcjt"/><path class="tgfgyvzbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:four-day-week" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jffa7dcjt {
  d: path("M7.875 4.5h8.25A4.375 4.375 0 0 1 20.5 8.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-8.25A4.375 4.375 0 0 1 3.5 17.125v-8.25A4.375 4.375 0 0 1 7.875 4.5M8 2.5v4m8-4v4m-12.5 3h17");
}

.tgfgyvzbz {
  d: path("M13.75 18.5v-6.25l-5 4h7");
}

</style>
