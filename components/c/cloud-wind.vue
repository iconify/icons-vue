<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwbd6qx7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cloud-wind" /></template>
<style>
.bwbd6qx7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 16.5a3 3 0 0 1 0-6a4 4 0 0 1 7 1.5a2.5 2.5 0 0 1-1.5 4.5ZM2.5 9h7m-7 4h5M4 17h5.5");
}

</style>
