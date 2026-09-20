<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="y63ozfbbb"/><path class="md51ihzsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-double-left-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.md51ihzsv {
  d: path("M203.06 40.61a8 8 0 0 0-8.72 1.73l-80 80a8 8 0 0 0 0 11.32l80 80A8 8 0 0 0 208 208V48a8 8 0 0 0-4.94-7.39M192 188.69L131.31 128L192 67.31Zm-66.34 13.65a8 8 0 0 1-11.32 11.32l-80-80a8 8 0 0 1 0-11.32l80-80a8 8 0 0 1 11.32 11.32L51.31 128Z");
}

.y63ozfbbb {
  d: path("M200 48v160l-80-80Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
