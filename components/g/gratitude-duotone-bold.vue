<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sf9h8ybif"/><path class="ym8p8xb-h"/><path class="f2w6xorcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gratitude-duotone-bold" /></template>
<style>
.f2w6xorcc {
  d: path("M6 7a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sf9h8ybif {
  fill: currentColor;
  d: path("M6 7a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ym8p8xb-h {
  d: path("M20 13a8 8 0 0 1 -16 0");
}

</style>
