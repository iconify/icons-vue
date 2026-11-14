<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhq7yobwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gift-option" /></template>
<style>
.jhq7yobwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8h8.5A1.75 1.75 0 0 1 15 9.75v.5A1.75 1.75 0 0 1 13.25 12h-8.5A1.75 1.75 0 0 1 3 10.25v-.5A1.75 1.75 0 0 1 4.75 8m-.25 4v5.5q0 3 3 3h3q1.427 0 2.175-.679m.825-4.334V12M9 8v12.5M9 8C8 4.5 5 3.5 5 5.25S7.5 8 9 8m0 0c1-3.5 4-4.5 4-2.75S10.5 8 9 8m5.75 10l2 2L21 15.75");
}

</style>
