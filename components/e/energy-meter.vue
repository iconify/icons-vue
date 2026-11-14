<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jq3xg-b1p"/><path class="y1us58bcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:energy-meter" /></template>
<style>
.jq3xg-b1p {
  d: path("M4 2.5h16v15H4Zm5 15v4m6-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y1us58bcv {
  d: path("M7.5 10a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm4.5 0l1.5-1.5");
}

</style>
