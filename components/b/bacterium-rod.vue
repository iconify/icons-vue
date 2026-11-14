<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxo2facov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bacterium-rod" /></template>
<style>
.mxo2facov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.49 15.207l6.717-6.717a1.75 1.75 0 0 1 2.475 0l2.828 2.828a1.75 1.75 0 0 1 0 2.475L8.793 20.51a1.75 1.75 0 0 1-2.475 0L3.49 17.682a1.75 1.75 0 0 1 0-2.475ZM14.25 9.75c2.25-.5.75-3 2.75-3.5s1-3 3-3.25c.75-.1 1.25 0 1.5-.5");
}

</style>
