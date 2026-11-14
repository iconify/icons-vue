<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1wbbvgrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bounce-rate" /></template>
<style>
.w1wbbvgrg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.75 6.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M2.5 20.5h19M3 4h.01M4 7.25h.01m1.24 3.25h.01m1.49 3.25h.01M8.5 17h.01M11 14.5h.01m1.99-3h.01M15 9h.01");
}

</style>
