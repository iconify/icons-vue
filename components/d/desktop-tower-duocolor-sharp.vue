<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w9j05kbxw"/><path class="wp-nfcbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:desktop-tower-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w9j05kbxw {
  stroke-opacity: 0.4;
  d: path("M6 20h3");
}

.wp-nfcbdv {
  d: path("M13 4h8v16h-8Zm0 5H3v8h10m4-9h.01M17 13v3");
}

</style>
