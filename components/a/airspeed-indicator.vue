<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv05h_dxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airspeed-indicator" /></template>
<style>
.vv05h_dxa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M6 15.5l-2.25 1.25M6 8.5L3.75 7.25M12 5V2.5m6 6l2.25-1.25M18 15.5l2.25 1.25M12 12l2.75-4.75M12 12h.01");
}

</style>
