<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j90vb6xsh"/><path class="ss008lb1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-close-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j90vb6xsh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 9v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5");
}

.ss008lb1o {
  d: path("M11 2h2a3 3 0 1 1 0 6h-2a3 3 0 1 1 0-6m-.293 10.293L12 13.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 15l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 16.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 15l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
