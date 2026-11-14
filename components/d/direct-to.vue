<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anr93cbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:direct-to" /></template>
<style>
.anr93cbeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 18.5L10 14m-3 0h3v3m7.793-11.802l2.377 4.041a1.5 1.5 0 0 1-1.293 2.261h-4.754a1.5 1.5 0 0 1-1.293-2.261l2.377-4.041a1.5 1.5 0 0 1 2.586 0M3.5 20.5h.01");
}

</style>
