<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r4cg_d1vy"/><path class="isanxq7-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gauge-target" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.isanxq7-v {
  fill: currentColor;
  d: path("M20.356 7.541za.75.75 0 0 1 .093 1.057l-2.893 3.447a.75.75 0 0 1-1.056.093a.75.75 0 0 1-.093-1.057L19.3 7.634a.75.75 0 0 1 1.056-.093");
}

.r4cg_d1vy {
  d: path("M2.5 17.5a9.5 9.5 0 0 1 19 0m-19 0h19m-9.5 0L7.25 11");
}

</style>
