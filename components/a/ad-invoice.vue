<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="ecr2iyzfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ad-invoice" /></template>
<style>
.ecr2iyzfa {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-5.5 3c-.25-1-1.25-1.5-2.5-1.5c-1.5 0-2.5.75-2.5 2c0 2.5 5 1.5 5 4.5c0 1.25-1 2-2.5 2c-1.25 0-2.25-.5-2.5-1.25m2.5-8.5V10m0 8.5v1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
