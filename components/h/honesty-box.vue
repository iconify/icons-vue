<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rf8942b8g"/><path class="dcb6qmb6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:honesty-box" /></template>
<style>
.dcb6qmb6u {
  d: path("M9 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-6 6h18");
}

.rf8942b8g {
  d: path("M6.25 8H5a2 2 0 0 0-2 2v8.5a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V10a2 2 0 0 0-2-2h-1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
