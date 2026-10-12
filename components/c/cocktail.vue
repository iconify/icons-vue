<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msj0s_bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cocktail" /></template>
<style>
.msj0s_bgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 2.75h2.5m-6 7.5C7.5 7.5 9.5 5.75 12 5.75s4.5 1.75 4.75 4.5Zm.75 0h8q1.25 0 1.11 1.24l-.97 8.52q-.14 1.24-1.39 1.24h-5.5q-1.25 0-1.39-1.24l-.97-8.52Q6.75 10.25 8 10.25m-.85 3.25h9.7");
}

</style>
