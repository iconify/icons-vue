<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g-qae1b1k"/><path class="bt66p3zww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bar-mat" /></template>
<style>
.bt66p3zww {
  d: path("M8.75 6.75h9l-1.75 4H7Zm10 9.75c1 1.25 1.75 2.25 1.75 3.25a1.75 1.75 0 0 1-3.5 0c0-1 .75-2 1.75-3.25Z");
}

.g-qae1b1k {
  d: path("M6 4h15.5L18 13.5H2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
