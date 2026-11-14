<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ybdotmbat"/><path class="ng3v8kb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-run-all" /></template>
<style>
.ng3v8kb3m {
  d: path("M8.25 7L6 9.5L8.25 12m3-5l2.25 2.5l-.827.919m.577 4.081l4 3.25l-4 3.25Zm4.5 0l4 3.25l-4 3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ybdotmbat {
  d: path("M10.4 19H3V2.5h13.5v9.1");
}

</style>
