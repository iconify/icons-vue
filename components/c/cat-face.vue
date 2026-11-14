<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op9143b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cat-face" /></template>
<style>
.op9143b9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 11l.75-7.5L10 7q2-.5 4 0l4.25-3.5L19 11c0 5.75-3.25 9.5-7 9.5S5 16.75 5 11m4.5 4.25l-7-1m7 3.75L3 19.5m11.5-4.25l7-1m-7 3.75l6.5 1.5M9.25 12h.01m5.49 0h.01");
}

</style>
