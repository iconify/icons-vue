<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xc70yzw7w"/><path class="hyukdsb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gavel-duocolor-round" /></template>
<style>
.hyukdsb-f {
  d: path("m17 6l3 3a1.414 1.414 0 0 1 0 2l-2 2a1.414 1.414 0 0 1-2 0l-5-5a1.414 1.414 0 0 1 0-2l2-2a1.414 1.414 0 0 1 2 0zm-4 14h8");
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
