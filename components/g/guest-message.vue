<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tnsp6xb2l"/><path class="unr4debip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:guest-message" /></template>
<style>
.tnsp6xb2l {
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h13A2.5 2.5 0 0 1 21 5.5v10a2.5 2.5 0 0 1-2.5 2.5H11l-4 3.5V18H5.5A2.5 2.5 0 0 1 3 15.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.unr4debip {
  d: path("M10 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2 7c0-1.4 1.75-2.25 4-2.25s4 .85 4 2.25");
}

</style>
