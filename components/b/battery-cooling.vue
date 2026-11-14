<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twssgzbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-cooling" /></template>
<style>
.twssgzbfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.9 16H2.5V5h17v7.4m0-3.65h1a1 1 0 0 1 1 1v1.5a1 1 0 0 1-1 1h-1m-1 3v6.5m-2.75-5l5.5 3.5m-5.5 0l5.5-3.5");
}

</style>
