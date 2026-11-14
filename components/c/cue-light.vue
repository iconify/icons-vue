<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlw1b1bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cue-light" /></template>
<style>
.vlw1b1bbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm6.907-7.987a8.5 8.5 0 0 1 5.08 5.08m0 5.814a8.5 8.5 0 0 1-5.08 5.08m-5.814 0a8.5 8.5 0 0 1-5.08-5.08m0-5.814a8.5 8.5 0 0 1 5.08-5.08");
}

</style>
