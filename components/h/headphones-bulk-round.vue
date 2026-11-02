<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ub5v1ibuf"/><path class="onffe2clz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:headphones-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.onffe2clz {
  d: path("M4.629 8.886A8.002 8.002 0 0 1 20 12a1 1 0 0 1-2 0a6 6 0 1 0-12 0a1 1 0 0 1-2 0a7.9 7.9 0 0 1 .629-3.114");
}

.ub5v1ibuf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 14a3 3 0 0 1 3-3h1a3 3 0 0 1 3 3v3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm13 0a3 3 0 0 1 3-3h1a3 3 0 0 1 3 3v3a3 3 0 0 1-3 3h-1a3 3 0 0 1-3-3Z");
}

</style>
