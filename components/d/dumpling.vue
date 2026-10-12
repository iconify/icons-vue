<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwb1vubpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dumpling" /></template>
<style>
.lwb1vubpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15c1.25 2.5 4.5 3.75 8.5 3.75s7.25-1.25 8.5-3.75a2.83 2.83 0 0 0-1.62-4.26a3.1 3.1 0 0 0-4.25-2.64a3.26 3.26 0 0 0-5.26 0a3.1 3.1 0 0 0-4.25 2.64A2.83 2.83 0 0 0 3.5 15m6-6.25l.75 2m4.25-2l-.75 2m-8 .75l1.5 1.25m11-1.25l-1.5 1.25M3 21.25h18");
}

</style>
