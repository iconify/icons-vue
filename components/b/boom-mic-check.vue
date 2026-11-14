<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv409sb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boom-mic-check" /></template>
<style>
.pv409sb9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.25L10.75 9M13 4a2 2 0 0 1 3 0a2 2 0 0 1 3 0a3 3 0 0 1 0 6a2 2 0 0 1-3 0a2 2 0 0 1-3 0a3 3 0 0 1 0-6Zm1.75 14l2 2L21 15.75");
}

</style>
