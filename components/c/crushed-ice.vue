<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yguc68k9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crushed-ice" /></template>
<style>
.yguc68k9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 12l1.5 9.5h11L19 12M5 12l1-3.5L9.5 7l2-3.5L15 5l.5 3l3 1l.5 3Zm4.5-5L9 12m6.5-4l-1 4");
}

</style>
