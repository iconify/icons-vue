<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p12lb0siu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drone-view" /></template>
<style>
.p12lb0siu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 9h6v6H9ZM4 4l5 5m11-5l-5 5M4 20l5-5m11 5l-5-5M2.5 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm16 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-16 16a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm16 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
