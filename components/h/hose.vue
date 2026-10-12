<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="o8w52mbli"/><path class="cdf13kz-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hose" /></template>
<style>
.cdf13kz-j {
  d: path("M14.5 9.75a2.5 2.5 0 1 1-5 0a2.5 2.5 0 1 1 5 0m-7 5.5l-2 6m11-6l2 6m-14.25 0h3m10 0h3M19 9.75h2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8w52mbli {
  cx: 12px;
  cy: 9.75px;
  r: 7px;
}

</style>
