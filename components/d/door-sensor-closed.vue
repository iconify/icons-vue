<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyo7z8nfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:door-sensor-closed" /></template>
<style>
.wyo7z8nfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 4h1A3.5 3.5 0 0 1 12 7.5v9A3.5 3.5 0 0 1 8.5 20h-1A3.5 3.5 0 0 1 4 16.5v-9A3.5 3.5 0 0 1 7.5 4m9.75 0za2.5 2.5 0 0 1 2.5 2.5v11a2.5 2.5 0 0 1-2.5 2.5a2.5 2.5 0 0 1-2.5-2.5v-11a2.5 2.5 0 0 1 2.5-2.5M8 8h.01");
}

</style>
