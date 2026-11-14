<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dgcw4wxkq"/><path class="omo0fdcrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:first-contact" /></template>
<style>
.dgcw4wxkq {
  d: path("M3 11a9 3 0 1 0 18 0a9 3 0 1 0-18 0Z");
}

.omo0fdcrs {
  d: path("M7.5 8.5a4.5 4.5 0 0 1 9 0M4 20h16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
