<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hwn02cc6z"/><path class="w6w9_rb0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fox-duocolor-round" /></template>
<style>
.hwn02cc6z {
  stroke-opacity: 0.4;
  d: path("m9 12l1 1m5-1l-1 1m-2 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w6w9_rb0g {
  d: path("m19 10l1 3l-7 7a1.414 1.414 0 0 1-2 0l-7-7l1-3V5c0-.738.631-1.369 1-1l3 3c.64.64 1.72 1 3 1s2.36-.36 3-1l3-3c.369-.369 1 .262 1 1z");
}

</style>
