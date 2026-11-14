<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwhwt3blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bench-backless" /></template>
<style>
.fwhwt3blv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7h16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 10H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 7m1.5 3v7m13-7v7m-13-3h13");
}

</style>
