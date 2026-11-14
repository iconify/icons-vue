<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nilsoew6v"/><path class="coibfaczt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cardboard-sheet" /></template>
<style>
.coibfaczt {
  d: path("M8.75 8q1.5-1.5 3 0t3 0t3 0M7.5 12q1.5-1.5 3 0t3 0t3 0M6.25 16q1.5-1.5 3 0t3 0t3 0");
}

.nilsoew6v {
  d: path("M7 3.5h14.5l-4.5 17H2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
