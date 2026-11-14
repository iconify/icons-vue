<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1upv0bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bighorn-sheep" /></template>
<style>
.z1upv0bar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8h6l-.5 8.5q-2.5 4-5 0Zm0 0C6.5 3 2.5 4.5 2.5 9.5c0 4.5 4 5 4 1.5M15 8c2.5-5 6.5-3.5 6.5 1.5c0 4.5-4 5-4 1.5");
}

</style>
