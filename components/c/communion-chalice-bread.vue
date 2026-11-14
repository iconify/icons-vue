<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5g0p5m5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:communion-chalice-bread" /></template>
<style>
.c5g0p5m5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8h13c0 4.5-3 6.5-6.5 6.5s-6.5-2-6.5-6.5m6.5 6.5V20m-4 0h8M8 8a4 4 0 0 1 8 0");
}

</style>
