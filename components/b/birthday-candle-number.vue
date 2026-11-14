<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahr_pqufg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:birthday-candle-number" /></template>
<style>
.ahr_pqufg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 11.5L12.5 9v12m-3 0h6m-3-14.75C11.1 5.4 11 3.9 12.5 2c1.5 1.9 1.4 3.4 0 4.25");
}

</style>
