<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvwz93bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-powder" /></template>
<style>
.xvwz93bam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 10.75h13V21.5h-13Zm0 3.5h13M7 8c-1.5 0-1.5-2.5.5-2.5C8 3 11 2.5 12 4c1-1.5 4-1 4.5 1.5c2 0 2 2.5.5 2.5Z");
}

</style>
