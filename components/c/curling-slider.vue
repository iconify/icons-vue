<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mil_iqb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curling-slider" /></template>
<style>
.mil_iqb1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 14V7a2 2 0 0 1 2-2h3.5l2 4l7 1.5c2 .5 3 1.5 3 3.5Zm0 2.5h17.5V19H3.25Z");
}

</style>
