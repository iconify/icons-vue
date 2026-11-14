<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uonr9ccrq"/><path class="msx4vwbsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clerestory-window" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.msx4vwbsv {
  d: path("M8.5 12h7a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 14v-.5A1.5 1.5 0 0 1 8.5 12m1.75 0v3.5m3.5-3.5v3.5");
}

.uonr9ccrq {
  d: path("m4.646 9.475l6.25-5.078a1.75 1.75 0 0 1 2.208 0l6.25 5.078A1.75 1.75 0 0 1 20 10.833v8.417A1.75 1.75 0 0 1 18.25 21H5.75A1.75 1.75 0 0 1 4 19.25v-8.417a1.75 1.75 0 0 1 .646-1.358");
}

</style>
