<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c04yr_fzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fare-cap" /></template>
<style>
.c04yr_fzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8V4h18v4M5 10h14v3.25a2 2 0 0 0 0 4v3.25H5v-3.25a2 2 0 0 0 0-4Zm5 5.25h4");
}

</style>
