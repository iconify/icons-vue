<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tuq82lbhh"/><path class="w80whxt-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:file-py" /></template>
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

.w80whxt-s {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M6 21.5v-6h2.5a2 2 0 0 1 0 4H6m7.5-4l2.5 3l2.5-3m-2.5 3v3");
}

</style>
