<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q756wjm3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bug-critical" /></template>
<style>
.q756wjm3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 6za4.5 4.5 0 0 1 4.5 4.5v2A4.5 4.5 0 0 1 10 17a4.5 4.5 0 0 1-4.5-4.5v-2A4.5 4.5 0 0 1 10 6M8 6a2 2 0 0 1 4 0M5.5 9.5L3 8.5m2.5 5l-2.5 1m11.5-5l2.5-1m-2.5 5l2.5-1m2.295 3.909l1.339 2.52a1.75 1.75 0 0 1-1.545 2.571h-2.678a1.75 1.75 0 0 1-1.545-2.571l1.339-2.52a1.75 1.75 0 0 1 3.09 0m-1.545.091V18m0 1.75h.01");
}

</style>
