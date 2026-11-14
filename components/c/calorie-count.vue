<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-nr-ob8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calorie-count" /></template>
<style>
.e-nr-ob8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c0 2.5 4.5 4 4.5 8a4.5 4.5 0 0 1-9 0c0-2.5 1.5-4 2-5c.75 1.25 1.25 1.75 1.5 2.25c.25-1.75.25-3.5 1-5.25ZM2.5 17.75h19c-.5 2.75-18.5 2.75-19 0Z");
}

</style>
