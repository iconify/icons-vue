<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ql3kx3b1a"/><path class="t01jb1i7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bug-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ql3kx3b1a {
  stroke-opacity: 0.4;
  d: path("M7 11L4 8m3 5H3m5 3l-3 3m12-8l3-3m-3 5h4m-5 3l3 3");
}

.t01jb1i7d {
  d: path("M17 13V9a2 2 0 0 0-2-2H9a2 2 0 0 0-2 2v4a5 5 0 0 0 10 0M9 7a3 3 0 0 1 6 0m-3 4v7");
}

</style>
