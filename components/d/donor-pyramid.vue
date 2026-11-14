<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av9mczbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donor-pyramid" /></template>
<style>
.av9mczbye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 3.25h1A1.75 1.75 0 0 1 14.25 5v.5a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 9.75 5.5V5a1.75 1.75 0 0 1 1.75-1.75M7.75 10h1a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 8.75 14h-1A1.75 1.75 0 0 1 6 12.25v-.5A1.75 1.75 0 0 1 7.75 10m7.5 0h1A1.75 1.75 0 0 1 18 11.75v.5A1.75 1.75 0 0 1 16.25 14h-1a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 15.25 10m-11 6.75h1A1.75 1.75 0 0 1 7 18.5v.5a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 2.5 19v-.5a1.75 1.75 0 0 1 1.75-1.75m7.25 0h1a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 9.75 19v-.5a1.75 1.75 0 0 1 1.75-1.75m7.25 0h1a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 17 19v-.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
