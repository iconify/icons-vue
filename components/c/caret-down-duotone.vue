<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ycvek40fg"/><path class="cx4qeubjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-down-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cx4qeubjj {
  d: path("M215.39 92.94A8 8 0 0 0 208 88H48a8 8 0 0 0-5.66 13.66l80 80a8 8 0 0 0 11.32 0l80-80a8 8 0 0 0 1.73-8.72M128 164.69L67.31 104h121.38Z");
}

.ycvek40fg {
  d: path("m208 96l-80 80l-80-80Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
