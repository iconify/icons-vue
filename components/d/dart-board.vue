<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yugeds9td"/><path class="z41mhfzug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dart-board" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yugeds9td {
  d: path("M2.5 13.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0Z");
}

.z41mhfzug {
  d: path("M6 13.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm4.5 0h.01m-.01 0l9-9m0-2.25V4.5h2.25");
}

</style>
