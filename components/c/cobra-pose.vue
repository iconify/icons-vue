<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td0emebms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cobra-pose" /></template>
<style>
.td0emebms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM21.5 19.5H14c-3.5 0-5.5-4-6.5-8.5m0 0L5 19.5");
}

</style>
