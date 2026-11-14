<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5neydb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:allergen-label" /></template>
<style>
.g5neydb6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.615 13.953a2.5 2.5 0 0 0-.365.297c-1 1-1 3-2.5 4.5c-1.75 1.75-4.5 2-6.5 0s-1.75-4.75 0-6.5c1.5-1.5 3.5-1.5 4.5-2.5s1-3 2.5-4.5c1.75-1.75 4.5-2 6.5 0s1.75 4.75 0 6.5a5 5 0 0 1-.695.576M14 7h.01M17 10h.01M7 14h.01M10 17h.01m9.354-1.016l1.665 3.642a1.5 1.5 0 0 1-1.364 2.124h-3.33a1.5 1.5 0 0 1-1.364-2.124l1.665-3.642a1.5 1.5 0 0 1 2.728 0M18 16.25v1.5m0 2h.01");
}

</style>
