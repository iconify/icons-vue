<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgu-0rwhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:constellation-search" /></template>
<style>
.rgu-0rwhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 13a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m3-8a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m8-1.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5 6a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-3 8a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
