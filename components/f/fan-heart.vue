<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t17d0bbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fan-heart" /></template>
<style>
.t17d0bbym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 20.25q-.525 0-.9-.3c-2.7-2.2-5.85-4.85-5.85-8.45c0-2.2 1.65-3.9 3.75-3.9c1.25 0 2.25.6 3 1.65c.75-1.05 1.75-1.65 3-1.65c2.1 0 3.75 1.7 3.75 3.9c0 3.6-3.15 6.25-5.85 8.45q-.375.3-.9.3m5.75-17.5a6 6 0 0 1 6 6M15 6a2.75 2.75 0 0 1 3 3");
}

</style>
