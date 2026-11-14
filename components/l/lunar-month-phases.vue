<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsia95hde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lunar-month-phases" /></template>
<style>
.qsia95hde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9a3 3 0 0 0 0 6a4.5 4.5 0 0 1 0-6ZM9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm9.5-3a3 3 0 0 1 0 6a4.5 4.5 0 0 0 0-6Z");
}

</style>
