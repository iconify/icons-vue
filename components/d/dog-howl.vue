<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hugttlbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-howl" /></template>
<style>
.hugttlbit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 21.5L15 18l-5-4.5l4-.5l-3.5-4.5c1.5-1 3.5-.5 5 .5l3-4l1.5 5.5c1.5 2 1.75 5.5 1.75 11m-5.25-10h.01M7 3a3 3 0 1 0 1 4a2.5 2.5 0 0 1-1-4Z");
}

</style>
