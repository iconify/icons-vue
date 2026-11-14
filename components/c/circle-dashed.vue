<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t92c9sb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:circle-dashed" /></template>
<style>
.t92c9sb7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.65 2.644a9.5 9.5 0 0 1 5.627 3.25m1.65 2.857a9.5 9.5 0 0 1 0 6.498m-1.65 2.857a9.5 9.5 0 0 1-5.627 3.25m-3.3 0a9.5 9.5 0 0 1-5.627-3.25m-1.65-2.857a9.5 9.5 0 0 1 0-6.498m1.65-2.857a9.5 9.5 0 0 1 5.627-3.25");
}

</style>
