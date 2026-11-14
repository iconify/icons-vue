<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e2j23zbjh"/><path class="j72hfcbeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:calendar-holiday" /></template>
<style>
.e2j23zbjh {
  d: path("M7.375 4h9.25A4.375 4.375 0 0 1 21 8.375v8.75a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-8.75A4.375 4.375 0 0 1 7.375 4M8 2.5V6m8-3.5V6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j72hfcbeq {
  d: path("M9.75 12.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m2.25-6V8m0 9.5v1.25m-6.25-6h1.5m9.5 0h1.5");
}

</style>
