<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0a0zpblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grid-floor-3d" /></template>
<style>
.c0a0zpblu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.832 6.555l6.296 4.197a1.5 1.5 0 0 1 0 2.496l-6.296 4.197a1.5 1.5 0 0 1-1.664 0l-6.296-4.197a1.5 1.5 0 0 1 0-2.496l6.296-4.197a1.5 1.5 0 0 1 1.664 0M6 10l9 6M9 8l9 6m-3-6l-9 6m12-4l-9 6");
}

</style>
