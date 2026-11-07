<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h7-t2qbtf"/><path class="b8-a24bph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-plus-corner-duocolor-round" /></template>
<style>
.b8-a24bph {
  d: path("M11 19H7a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v2M4 7l3 3c.64.64 1.72 1 3 1h4c1.28 0 2.36-.36 3-1l3-3");
}

.h7-t2qbtf {
  stroke-opacity: 0.4;
  d: path("M15 18h6m-3-3v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
