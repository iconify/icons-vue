<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev3ji_5xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:downlight" /></template>
<style>
.ev3ji_5xn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h18M7 7c0 3 2.25 5 5 5s5-2 5-5m-5 8v3m-5-3.5L5.5 17M17 14.5l1.5 2.5");
}

</style>
