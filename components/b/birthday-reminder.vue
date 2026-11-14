<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t7g7kc2vl"/><path class="pgq6wfb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:birthday-reminder" /></template>
<style>
.pgq6wfb9g {
  d: path("M2.5 13q1.75 2 3.5 0q1.75 2 3.5 0q1.75 2 3.5 0q1.088 1.244 2.176.941M9.5 5.5v4m0-6.75h.01M15.5 20.5H21c-1-1-1-2-1-3.25a1.75 1.75 0 0 0-3.5 0c0 1.25 0 2.25-1 3.25Z");
}

.t7g7kc2vl {
  d: path("M13.7 18H2.5V9.5h14V13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
