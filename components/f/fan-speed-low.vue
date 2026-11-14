<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpt1zubsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fan-speed-low" /></template>
<style>
.mpt1zubsm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 12a3.75 3.75 0 0 1 0-7a3.75 3.75 0 0 1 0 7a3.75 3.75 0 0 1 6 3.5a3.75 3.75 0 0 1-6-3.5a3.75 3.75 0 0 1-6 3.5a3.75 3.75 0 0 1 6-3.5m8.192-5.736a10 10 0 0 1 0 11.472");
}

</style>
