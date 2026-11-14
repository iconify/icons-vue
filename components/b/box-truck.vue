<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aa6v5lj4o"/><path class="kcya__xav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:box-truck" /></template>
<style>
.aa6v5lj4o {
  d: path("M5.125 5h7.75A2.625 2.625 0 0 1 15.5 7.625v6.25a2.625 2.625 0 0 1-2.625 2.625h-7.75A2.625 2.625 0 0 1 2.5 13.875v-6.25A2.625 2.625 0 0 1 5.125 5M15.5 8.5H19l2.5 3.5v4.5h-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kcya__xav {
  d: path("M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-12.5-8h13");
}

</style>
