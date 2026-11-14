<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cvwgebbhj"/><path class="tkpegez4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chatbot-greeting" /></template>
<style>
.cvwgebbhj {
  d: path("M6.5 6.5h11A2.5 2.5 0 0 1 20 9v6.5a2.5 2.5 0 0 1-2.5 2.5H11l-4 3v-3h-.5A2.5 2.5 0 0 1 4 15.5V9a2.5 2.5 0 0 1 2.5-2.5ZM12 2.75V6.5M9.5 12h.01m4.99 0h.01");
}

.tkpegez4g {
  d: path("M9.75 14.75c1.25 1 3.25 1 4.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
