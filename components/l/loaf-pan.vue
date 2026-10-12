<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7k3oxb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loaf-pan" /></template>
<style>
.v7k3oxb4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11c0-3.5 3-5.75 7-5.75S19 7.5 19 11Zm0 0h14q1.25 0 1.05 1.23l-1.1 6.79q-.2 1.23-1.45 1.23h-11q-1.25 0-1.45-1.23l-1.1-6.79Q3.75 11 5 11m-1.25 0h-1m17.5 0h1");
}

</style>
