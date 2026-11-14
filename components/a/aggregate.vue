<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ish8tiu1k"/><path class="u4godzowz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aggregate" /></template>
<style>
.ish8tiu1k {
  fill: currentColor;
  d: path("M15.5 10h6v4h-6Z");
}

.u4godzowz {
  d: path("M9.5 4.5c1.5 0 2 .75 2 2.25v3c0 1.5.5 2.25 1.75 2.25c-1.25 0-1.75.75-1.75 2.25v3c0 1.5-.5 2.25-2 2.25M2.5 6H7m-4.5 6H7m-4.5 6H7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
