<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lwdgl7bfy"/><path class="mahsv7rtz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-check-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lwdgl7bfy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 7a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5h-6a5 5 0 0 1-5-5Z");
}

.mahsv7rtz {
  d: path("M11.707 9.293L13 10.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414M4 9v8a3 3 0 0 0 3 3h8a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V9a1 1 0 0 1 2 0");
}

</style>
