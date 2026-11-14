<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgyns2_4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guiro" /></template>
<style>
.lgyns2_4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14a8.5 5 0 1 0 17 0a8.5 5 0 1 0-17 0m5.5-2v4m3-4v4m3-4v4M3 4l18 4");
}

</style>
