<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp2k9ac4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:acid-rain-cloud" /></template>
<style>
.wp2k9ac4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13.25a4 4 0 0 1-.75-7.75a6.5 6.5 0 0 1 10.5.5a3.75 3.75 0 0 1 .25 7.25Zm-1.5 3l-1.5 4m5.5-4l-1.5 4m5.5-4l-1.5 4M18.25 16c.75 1 2.25 2.5 2.25 3.5a2.25 2.25 0 0 1-4.5 0c0-1 1.5-2.5 2.25-3.5");
}

</style>
