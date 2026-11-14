<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lpgyrtalg"/><path class="f8znq2r-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eco-shopping-trolley" /></template>
<style>
.f8znq2r-c {
  d: path("M12.5 9c0-3.5 2-5.5 5.5-6c0 3.5-2 5.75-5.5 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpgyrtalg {
  d: path("M2.5 4.5H5L7.5 16H18l2.5-7H6m1.5 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m7.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
