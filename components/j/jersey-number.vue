<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="huu46sbau"/><path class="oad71bc0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jersey-number" /></template>
<style>
.huu46sbau {
  d: path("M8 3L3 6l1.5 4.5l2.5-1V21h10V9.5l2.5 1L21 6l-5-3q-4 3.5-8 0Z");
}

.oad71bc0a {
  d: path("M9.75 11.75h4.5l-2.75 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
