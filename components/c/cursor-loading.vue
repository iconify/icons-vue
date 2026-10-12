<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfu66qx_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cursor-loading" /></template>
<style>
.wfu66qx_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.9 4.24l9.95 4.27q1.15.49-.04.87l-3.12.99q-1.19.38-1.63 1.55l-1.37 3.66q-.44 1.17-.85-.01L5.16 4.93q-.41-1.18.74-.69m11.35 9.51a3.5 3.5 0 1 1-3.5 3.5");
}

</style>
