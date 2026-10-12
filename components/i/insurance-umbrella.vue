<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2eevkbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insurance-umbrella" /></template>
<style>
.h2eevkbgd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 11.75a8.75 8.75 0 0 1 17.5 0a3.75 3.75 0 0 0-5.83 0a3.75 3.75 0 0 0-5.84 0a3.75 3.75 0 0 0-5.83 0m4.5 8.5v-2.5q0-1 .77-1.64l2.71-2.22q.77-.64 1.54 0l2.71 2.22q.77.64.77 1.64v2.5q0 1-1 1h-6.5q-1 0-1-1");
}

</style>
