<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg4b21bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dry-run" /></template>
<style>
.vg4b21bbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.329 3.307a9 9 0 0 1 6.364 6.364m0 4.658a9 9 0 0 1-6.364 6.364m-4.658 0a9 9 0 0 1-6.364-6.364m0-4.658a9 9 0 0 1 6.364-6.364m2.996 6.334l1.411.869a1.75 1.75 0 0 1 0 2.98l-1.411.869A1.75 1.75 0 0 1 10 12.868v-1.736a1.75 1.75 0 0 1 2.667-1.491");
}

</style>
