<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ognr3yb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-pedal" /></template>
<style>
.ognr3yb8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 15.5L4.5 9A2.5 2.5 0 0 1 8 5.5l10 10m-7.5 0h8a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2a2 2 0 0 1 2-2M6.25 7.25h.01");
}

</style>
