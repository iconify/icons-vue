<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekygtbc8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camshaft" /></template>
<style>
.ekygtbc8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19M4 10.5a1.75 4 0 1 0 3.5 0a1.75 4 0 1 0-3.5 0Zm6.25 3a1.75 4 0 1 0 3.5 0a1.75 4 0 1 0-3.5 0Zm6.25-3a1.75 4 0 1 0 3.5 0a1.75 4 0 1 0-3.5 0Z");
}

</style>
