<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvrb7hvlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fog-light" /></template>
<style>
.pvrb7hvlk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5.5v13c-4.5 0-7.5-3-7.5-6.5s3-6.5 7.5-6.5m3 2.25q2-1.5 4 0t4 0M13 12q2-1.5 4 0t4 0m-8 4.25q2-1.5 4 0t4 0");
}

</style>
