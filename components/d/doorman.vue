<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igy1fpbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:doorman" /></template>
<style>
.igy1fpbcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4.25c0-1.75 11-1.75 11 0L15.75 6.5h-7.5Zm8.748 4.125a3.75 3.75 0 1 1-6.496 0M4.5 21.5c0-3.5 3.25-5.25 7.5-5.25s7.5 1.75 7.5 5.25M8.25 6.5c1.25 1.75 6.25 1.75 7.5 0");
}

</style>
