<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr68auzbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-heating" /></template>
<style>
.lr68auzbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11h9a3.5 3.5 0 0 1 3.5 3.5v2a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 3 16.5v-2A3.5 3.5 0 0 1 6.5 11M19 13.75h1.5v3.5H19M7 8Q6 6.875 7 5.75T7 3.5M11 8q-1-1.125 0-2.25t0-2.25M15 8q-1-1.125 0-2.25t0-2.25");
}

</style>
