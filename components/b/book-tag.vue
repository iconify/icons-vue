<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jrrue0b1c"/><path class="hx9vpzbld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:book-tag" /></template>
<style>
.hx9vpzbld {
  d: path("M2.5 19A2.5 2.5 0 0 1 5 16.5h8.5m0-10.5l5.75 3l2.5 3v8.5H16.5V12l2.75-3m0 4.25h.01");
}

.jrrue0b1c {
  d: path("M2.5 19V5A2.5 2.5 0 0 1 5 2.5h8.5v19H5A2.5 2.5 0 0 1 2.5 19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
