<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xc70yzw7w"/><path class="d7xyhx1vs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hammer-duocolor-round" /></template>
<style>
.d7xyhx1vs {
  d: path("m9 3l1 1c1.28 1.28 2 2.72 2 4v2l2 2h1c.64 0 1.36.36 2 1a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 0 0-2c-.64-.64-1-1.36-1-2s-.36-1.36-1-2l-1-1c-1.28-1.28-2.72-2-4-2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xc70yzw7w {
  stroke-opacity: 0.4;
  d: path("m15 12l-8 8a2.121 2.121 0 1 1-3-3l8-8");
}

</style>
