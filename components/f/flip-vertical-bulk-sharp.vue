<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gyyhg0bpe"/><path class="jvfhggt3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gyyhg0bpe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.293 3.707A1 1 0 0 1 7 2h10a1.002 1.002 0 0 1 .707 1.707l-5 5a1 1 0 0 1-1.414 0Zm0 16.586l5-5a1 1 0 0 1 1.414 0l5 5A1 1 0 0 1 17 22H7a1.002 1.002 0 0 1-.707-1.707");
}

.jvfhggt3x {
  d: path("M7 11a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Z");
}

</style>
