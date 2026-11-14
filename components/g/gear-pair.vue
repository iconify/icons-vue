<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="prfokx1tc"/><path class="bwqmrlzgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gear-pair" /></template>
<style>
.bwqmrlzgh {
  d: path("M7 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.prfokx1tc {
  d: path("m12.5 8.25l1.5.5l-.75 2.25l-1.5-.25l-1 1l.25 1.5l-2.25.75l-.5-1.5l-1.5-.25l-1.25 1l-1.75-1.75l1-1.25l-.25-1.5l-1.5-.5L3.75 6l1.5.25l1-1L6 3.75L8.25 3l.5 1.5l1.5.25l1.25-1l1.75 1.75l-1 1.25Zm6.75 8.5l-.25.75l.75 1l-1.25 1.25l-1-.75l-.75.25l-.25 1l-1.75-.5v-1l-.5-.5h-1l-.5-1.75l1-.25l.25-.75l-.75-1l1.25-1.25l1 .75l.75-.25l.25-1l1.75.5v1l.5.5h1l.5 1.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
