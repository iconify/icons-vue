<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kr-izc7tx"/><path class="qojv_-bmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:demolition" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kr-izc7tx {
  d: path("M14.25 6h5.5a1.75 1.75 0 0 1 1.75 1.75v12a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75v-12A1.75 1.75 0 0 1 14.25 6M3.5 14.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m.5-12l2.5 9");
}

.qojv_-bmk {
  d: path("m17 6l-1.25 4L18 13l-1.5 3");
}

</style>
