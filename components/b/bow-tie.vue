<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqtuv01cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bow-tie" /></template>
<style>
.vqtuv01cc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 10L4 6.5c-1-.5-1.5 0-1.5 1v9c0 1 .5 1.5 1.5 1l6-3.5m4-4l6-3.5c1-.5 1.5 0 1.5 1v9c0 1-.5 1.5-1.5 1L14 14m-4-4.5h4v5h-4Z");
}

</style>
