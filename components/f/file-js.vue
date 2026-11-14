<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tuq82lbhh"/><path class="y_0ry_bsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:file-js" /></template>
<style>
.tuq82lbhh {
  d: path("M4.5 12V5A2.5 2.5 0 0 1 7 2.5h6.5l6 6V12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_0ry_bsf {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M8 15.5h2.5v3.75a2.25 2.25 0 0 1-4.5 0m12.25-3c-.5-.75-4.5-1-4.5.75c0 2 4.75.75 4.75 2.75s-4.25 2-5 .75");
}

</style>
