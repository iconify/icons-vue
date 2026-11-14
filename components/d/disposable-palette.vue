<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bqddp2b0w"/><path class="po9otjbvo"/><path class="t5osdifez"/><path class="x5ki3dbml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:disposable-palette" /></template>
<style>
.bqddp2b0w {
  d: path("M2.5 12a9.5 8 0 1 0 19 0a9.5 8 0 1 0-19 0Z");
}

.po9otjbvo {
  d: path("M8.25 15.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.t5osdifez {
  fill: currentColor;
  d: path("M5.75 10.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm5-2.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm5 2.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5ki3dbml {
  d: path("M14.5 19.75Q15 15 21 14.5");
}

</style>
