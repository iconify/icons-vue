<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh-issc0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fast-food-restaurant" /></template>
<style>
.xh-issc0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14a4.75 4.75 0 0 1 9.5 0Zm2 3H10a2 2 0 0 1 2 2a2 2 0 0 1-2 2H4.5a2 2 0 0 1-2-2a2 2 0 0 1 2-2m10.25-7h6.75l-1 11h-4.75Zm2 0V4.5M19.5 10V5.5");
}

</style>
