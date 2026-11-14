<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5s_x0y7o"/><path class="m4bulibns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:egg-development" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m4bulibns {
  d: path("m15.5 5.5l2.25 1.25L16 8");
}

.o5s_x0y7o {
  d: path("M4.75 12.5L8 11l2 2l2-2l2 2l2-2l3.25 1.5c0 5-3 8-7.25 8s-7.25-3-7.25-8M8 11V7.5a4 4 0 0 1 8 0V11m-3-4.25h.01");
}

</style>
