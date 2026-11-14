<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpwzdub6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emergency-meeting-point" /></template>
<style>
.fpwzdub6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 3l4.75 4.75m0-3.5v3.5h-3.5M21 3l-4.75 4.75m0-3.5v3.5h3.5M3 21l4.75-4.75m0 3.5v-3.5h-3.5M21 21l-4.75-4.75m0 3.5v-3.5h3.5M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
