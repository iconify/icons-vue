<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmz33zbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forecast-rollup" /></template>
<style>
.rmz33zbfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3v17.5h9.6m-6.1-3V13m3 4.5v-4.9m0-.4V9.5m3 8v-1.6m0-3.7V6m8.5 9H16l3 3.25l-3 3.25h5.5");
}

</style>
