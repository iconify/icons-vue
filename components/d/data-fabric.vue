<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeef4z2vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-fabric" /></template>
<style>
.qeef4z2vs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 3.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M2 12a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 2 12m16.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-8.25 8.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M9.75 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m3.5-7L19 10.75m0 2.5L13.25 19m-2.5 0L5 13.25m0-2.5L10.75 5m1.25.5v4.25m0 4.5v4.25M5.5 12h4.25m4.5 0h4.25");
}

</style>
