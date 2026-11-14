<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocvm74uis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:displaced-family" /></template>
<style>
.ocvm74uis {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM2.5 20.5c0-4 2.25-6.5 5.25-6.5c1.75 0 3.245.851 4.187 2.354M15.25 7.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-.717 6.415c.125-.605.601-.995 1.305-1.209M14.25 18L18 14.5l3.75 3.5v3.75h-7.5Z");
}

</style>
