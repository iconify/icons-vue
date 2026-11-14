<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_x34fbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baseball-bunt" /></template>
<style>
.u_x34fbcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6h5.301a3 3 0 0 0 .395-.03l8.284-1.26a2.625 2.625 0 0 1 3.02 2.595v.39a2.625 2.625 0 0 1-3.02 2.595l-8.284-1.26A3 3 0 0 0 9.801 9H4.5A1.5 1.5 0 0 1 3 7.5A1.5 1.5 0 0 1 4.5 6m8 11a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
