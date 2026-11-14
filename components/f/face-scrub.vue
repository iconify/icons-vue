<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys-3wmbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-scrub" /></template>
<style>
.ys-3wmbtb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12.6v8.9H2.5V9H12v3.4M5 9V6.5h4.5V9M7.25 6.5v-3H11m4 15.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm4.5-6a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm-4.75-.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
