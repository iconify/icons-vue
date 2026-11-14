<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gihupnyfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cosmetic-dropper" /></template>
<style>
.gihupnyfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.875 11h2.25a4.375 4.375 0 0 1 4.375 4.375v1.25A4.375 4.375 0 0 1 13.125 21h-2.25A4.375 4.375 0 0 1 6.5 16.625v-1.25A4.375 4.375 0 0 1 10.875 11M9.5 11V8.5h5V11m-4-2.5V5a1.5 1.5 0 0 1 3 0v3.5");
}

</style>
