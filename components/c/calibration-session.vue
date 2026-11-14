<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg7acnb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calibration-session" /></template>
<style>
.xg7acnb1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3v18m8-18v18m8-18v18M3.25 12a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm8 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm8 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0ZM2 12h2m3.25 0h1.5m6.5 0h1.5M20 12h2");
}

</style>
