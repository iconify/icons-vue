<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djwr2ob9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chills" /></template>
<style>
.djwr2ob9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 14V5.5a2 2 0 0 1 4 0V14a4 4 0 1 1-4 0Zm11-8.5v7m-3-5.25l6 3.5m0-3.5l-6 3.5");
}

</style>
