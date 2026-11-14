<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1bmtgbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:effort-level" /></template>
<style>
.p1bmtgbik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5H12v3H2.5ZM12 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm7 0h2.5");
}

</style>
