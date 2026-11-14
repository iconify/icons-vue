<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jecdbkbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:corner-smoothing" /></template>
<style>
.jecdbkbvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 5.5c6.25 0 8 1.75 8 8s-1.75 8-8 8s-8-1.75-8-8s1.75-8 8-8m3.5-3h7.5V10");
}

</style>
