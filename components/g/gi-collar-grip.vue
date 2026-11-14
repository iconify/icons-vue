<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-vuu_yef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gi-collar-grip" /></template>
<style>
.g-vuu_yef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5V10c0-3 2-5 5.5-6.5m13.5 18V10c0-3-2-5-5.5-6.5m-8 0l3 7.5m5-7.5L13 11m-1.375 0h.75A2.625 2.625 0 0 1 15 13.625v.25a2.625 2.625 0 0 1-2.625 2.625h-.75A2.625 2.625 0 0 1 9 13.875v-.25A2.625 2.625 0 0 1 11.625 11M10.5 16.5v5m3-5v5");
}

</style>
