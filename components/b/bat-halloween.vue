<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0s295b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bat-halloween" /></template>
<style>
.h0s295b3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.05a3.75 3.75 0 1 0 2.75 4.6a3 3 0 0 1-2.75-4.6m3.5 10.7l1-1.5l.5 1.5c1.75-1 4.5-1.5 7.75-.5c-1.25 1-1.75 2.5-1.75 4c-1-.75-2.25-.75-3.25.25c-.75-.5-1.75-.25-2.25.75l-2 2l-2-2c-.5-1-1.5-1.25-2.25-.75c-1-1-2.25-1-3.25-.25c0-1.5-.5-3-1.75-4c3.25-1 6-.5 7.75.5l.5-1.5Z");
}

</style>
