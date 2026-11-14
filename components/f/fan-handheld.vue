<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biu0lhb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fan-handheld" /></template>
<style>
.biu0lhb2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 15l-8.5-3a4 4 0 0 1 3.25-4.25A4 4 0 0 1 12 6a4 4 0 0 1 5.25 1.75A4 4 0 0 1 20.5 12Zm0 0v5.5m0-5.5L6.75 7.75M12 15V6m0 9l5.25-7.25");
}

</style>
