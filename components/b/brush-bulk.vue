<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yp1b9dl6h"/><path class="qefa9xb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brush-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qefa9xb9o {
  d: path("M11 3v3a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m4 0v3a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0M6 9h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

.yp1b9dl6h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 15a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-1v4a3 3 0 1 1-6 0v-4Z");
}

</style>
