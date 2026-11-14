<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgdv0zjkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:balcony-garden" /></template>
<style>
.cgdv0zjkp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19m-19 7.5h19M6 14v7.5m6-7.5v7.5m6-7.5v7.5M5.87 9.5h2.26a1.5 1.5 0 0 1 1.464 1.825l-.333 1.5A1.5 1.5 0 0 1 7.797 14H6.203a1.5 1.5 0 0 1-1.464-1.175l-.333-1.5A1.5 1.5 0 0 1 5.87 9.5M7 9.5V4m0 2.5Q4.5 6.5 4.5 4M7 6.5q2.5 0 2.5-2.5m6.37 5.5h2.26a1.5 1.5 0 0 1 1.464 1.825l-.333 1.5A1.5 1.5 0 0 1 17.797 14h-1.594a1.5 1.5 0 0 1-1.464-1.175l-.333-1.5A1.5 1.5 0 0 1 15.87 9.5m1.13 0V3m0 3.5q2.5 0 2.5-3");
}

</style>
