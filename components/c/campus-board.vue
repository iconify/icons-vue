<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojajhytka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campus-board" /></template>
<style>
.ojajhytka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.375 2.5h7.398a1.75 1.75 0 0 1 1.701 2.164l-3.649 15a1.75 1.75 0 0 1-1.7 1.336H6.727a1.75 1.75 0 0 1-1.701-2.164l3.649-15a1.75 1.75 0 0 1 1.7-1.336M2.5 21h19M10.75 7.5h5m-7.25 9h5m-4-4.5h.01M14 12h.01");
}

</style>
