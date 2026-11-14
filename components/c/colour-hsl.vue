<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c34yo43sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-hsl" /></template>
<style>
.c34yo43sa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 12a6.25 6.25 0 1 0 12.5 0A6.25 6.25 0 1 0 2 12m6.25-6.25v12.5M2 12h12.5m5-8v16m-2-10a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
