<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co2p550nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-to-prayer-speaker" /></template>
<style>
.co2p550nh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 21l.75-11h3.5l.75 11Zm-1-11h7m-5 0V6.5l1.5-3l1.5 3V10m3-5.5l5-2V9l-5-2Zm-3 1.25h3");
}

</style>
