<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y7fwo2b4i"/><path class="lyluz8blw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drone-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lyluz8blw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 9h4v6h-4Zm0-4a3.605 3.605 0 1 0-5 5m14 0a3.605 3.605 0 1 0-5-5m0 14a3.605 3.605 0 1 0 5-5M5 14a3.605 3.605 0 1 0 5 5M7 7l3 3m7-3l-3 3m-7 7l3-3m7 3l-3-3");
}

.y7fwo2b4i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 15V9a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1");
}

</style>
