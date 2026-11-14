<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpz0sab2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-rate-zone" /></template>
<style>
.wpz0sab2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14a9 9 0 0 1 3-6.75m2.25-1.5a9 9 0 0 1 7.5 0M18 7.25A9 9 0 0 1 21 14m-9 5.5l-4.25-4.25a2.75 2.75 0 0 1 4.25-3.5a2.75 2.75 0 0 1 4.25 3.5Z");
}

</style>
