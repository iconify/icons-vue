<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wfyc1hbew"/><path class="aakm0mm-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-archive-bulk" /></template>
<style>
.aakm0mm-m {
  d: path("m13.707 2.293l6 6A1 1 0 0 1 19 10h-4a3 3 0 0 1-3-3V3a1.002 1.002 0 0 1 1.707-.707M14 5.414V7a.997.997 0 0 0 1 1h1.586ZM10.01 5a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm-2 2a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm2 2a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm-2 2a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2ZM13 18v2a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-2a3 3 0 1 1 6 0m-4 0v2h2v-2a1 1 0 0 0-2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.wfyc1hbew {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 21V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v10a3 3 0 0 1-3 3h-2a1 1 0 0 1-1-1v-3a4 4 0 0 0-8-.003V21a1 1 0 0 1-2 0m9-17v3a2 2 0 0 0 2 2h3Z");
}

</style>
