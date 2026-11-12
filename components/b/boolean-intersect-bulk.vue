<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dwreddrse"/><path class="rxwogcbqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-intersect-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dwreddrse {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 8h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2");
}

.rxwogcbqc {
  d: path("M4 2h3a1 1 0 0 1 0 2H4v3a1 1 0 0 1-2 0V3.999A2 2 0 0 1 4 2m7 0h3.001c.531 0 1.04.211 1.414.587c.375.376.586.882.585 1.413v1a1 1 0 0 1-2 0V4h-3a1 1 0 0 1 0-2m8 6h1a2 2 0 0 1 2 2v3a1 1 0 0 1-2 0v-3h-1a1 1 0 0 1 0-2M2 11a1 1 0 0 1 2 0v3h1a1 1 0 0 1 0 2H4a2 2 0 0 1-2-2Zm18 11h-3a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0v3a2 2 0 0 1-2 2M8 19a1 1 0 0 1 2 0v1h3a1 1 0 0 1 0 2h-3a2 2 0 0 1-2-2Z");
}

</style>
