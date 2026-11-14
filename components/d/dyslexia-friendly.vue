<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sas30ab3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dyslexia-friendly" /></template>
<style>
.sas30ab3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5v14m0-3a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm15-11v14m-6-3a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
