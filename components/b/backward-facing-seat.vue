<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m1ux16bsw"/><path class="cgsm60b6u"/><path class="ecvn2ubyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backward-facing-seat" /></template>
<style>
.cgsm60b6u {
  d: path("M12.5 10A4.5 4.5 0 0 0 8 5.5H6");
}

.ecvn2ubyo {
  d: path("M7.75 3.25L5.5 5.5l2.25 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1ux16bsw {
  d: path("M15.5 13V4.5a1.75 1.75 0 0 1 3.5 0v12H6A1.5 1.5 0 0 1 4.5 15v-.5A1.5 1.5 0 0 1 6 13Zm-4 3.5V21M8 21h7");
}

</style>
