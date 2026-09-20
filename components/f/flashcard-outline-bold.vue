<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h8b2rkgcl"/><path class="cu5fjhbmy"/><path class="qii79lbir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flashcard-outline-bold" /></template>
<style>
.cu5fjhbmy {
  d: path("M16 6v5h5");
}

.h8b2rkgcl {
  d: path("M3 6h13l5 5v7H3Z");
}

.qii79lbir {
  d: path("M6 14h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
