<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zf32l0bqo"/><path class="l13qv277c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:inbox-duocolor-round" /></template>
<style>
.l13qv277c {
  d: path("M3 8a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zf32l0bqo {
  stroke-opacity: 0.4;
  d: path("M3 13h2c1.28 0 2.36.36 3 1l1 1c.64.64 1.72 1 3 1s2.36-.36 3-1l1-1c.64-.64 1.72-1 3-1h2");
}

</style>
