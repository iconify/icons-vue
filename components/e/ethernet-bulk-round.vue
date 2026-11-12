<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cq19j9p9i"/><path class="dqguevbeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ethernet-bulk-round" /></template>
<style>
.cq19j9p9i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 18a3 3 0 0 1-3-3V8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v7a3 3 0 0 1-3 3h-1v2a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.dqguevbeq {
  d: path("M7 8v3a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m4 0v3a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m4 3a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0Zm4-3v3a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0");
}

</style>
