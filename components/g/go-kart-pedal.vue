<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1c-fybrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:go-kart-pedal" /></template>
<style>
.c1c-fybrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m13.25 1.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M3.25 4.5L5 10h5l1.5 2.75H21m-4 0L15 8m-1.75 1l3.5-2");
}

</style>
