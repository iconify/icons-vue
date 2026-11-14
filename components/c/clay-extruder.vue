<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="toe00dwfh"/><path class="e22wxgbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clay-extruder" /></template>
<style>
.e22wxgbut {
  d: path("M11.177 15.5h1.646a1.036 1.036 0 0 1 .927 1.5l-.335.671a1.5 1.5 0 0 1-1.342.829h-.146a1.5 1.5 0 0 1-1.342-.829L10.25 17a1.036 1.036 0 0 1 .927-1.5m.823 3V21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.toe00dwfh {
  d: path("M6 3h12m-6 0v3M9.625 6h4.75A2.625 2.625 0 0 1 17 8.625v4.25a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 7 12.875v-4.25A2.625 2.625 0 0 1 9.625 6");
}

</style>
