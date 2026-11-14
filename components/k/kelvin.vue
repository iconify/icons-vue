<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy0aa10_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kelvin" /></template>
<style>
.vy0aa10_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13.5V5a2.5 2.5 0 0 1 5 0v8.5a4.5 4.5 0 1 1-5 0M9 8v7.5M14.25 5H17m-2.75 4H17m-1.5 10.5h5");
}

</style>
