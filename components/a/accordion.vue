<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ndnygt_up"/><path class="ga8xxqb2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accordion" /></template>
<style>
.ga8xxqb2l {
  d: path("m15.5 5.25l1.5 1.5l1.5-1.5m-3 9.75l1.5-1.5l1.5 1.5M5 20.25h10");
}

.ndnygt_up {
  d: path("M2.5 3.25h19v5.5h-19Zm0 8.25h19V17h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
