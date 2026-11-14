<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5tys9l_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clothes-hanger" /></template>
<style>
.h5tys9l_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 7.5A2.25 2.25 0 1 1 12 9.75V12m1.655.845L16 14.75A1.83 1.83 0 0 1 14.846 18H9.154A1.83 1.83 0 0 1 8 14.75l2.345-1.905a2.625 2.625 0 0 1 3.31 0");
}

</style>
