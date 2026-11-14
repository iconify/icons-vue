<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="misndob5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-module" /></template>
<style>
.misndob5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6.5h11A3.5 3.5 0 0 1 21 10v5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 15v-5a3.5 3.5 0 0 1 3.5-3.5m0 0V4m11 2.5V4M9 6.5v12m6-12v12");
}

</style>
