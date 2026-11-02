<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yra2nkbxn"/><path class="gtawmvbqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:horse-duocolor-round" /></template>
<style>
.gtawmvbqi {
  d: path("M10 6V5c0-.738.631-1.369 1-1l2 2l4 1l-1 2l4 1l-1 2l2 2v3a4 4 0 0 1-4 4h-2a3 3 0 0 1-3-3c0-1.107-1.262-1.738-2-1l-1 1c-.64.64-1.72 1-3 1H5a2 2 0 0 1-2-2v-2c0-1.28.36-2.36 1-3z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yra2nkbxn {
  stroke-opacity: 0.4;
  d: path("M11 10h.01M6 16h.01");
}

</style>
