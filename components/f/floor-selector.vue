<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wasmt8b2b"/><path class="ymb2htbzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:floor-selector" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wasmt8b2b {
  d: path("M2.5 2.5h10v19h-10Zm2.75 4.75h4.5M5.25 12h4.5");
}

.ymb2htbzy {
  d: path("M6 21.5V17h3.25v4.5M15 9l3-3l3 3m-6 6l3 3l3-3");
}

</style>
