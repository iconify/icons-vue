<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ub-1t7bpu"/><path class="nc39x5bep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jersey" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nc39x5bep {
  d: path("M10 11.75h4l-2.25 6");
}

.ub-1t7bpu {
  d: path("m8.5 3.25l-5.5 3l1.75 4.25L7 9.5v11.75h10V9.5l2.25 1L21 6.25l-5.5-3a3.5 3.5 0 0 1-7 0");
}

</style>
