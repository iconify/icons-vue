<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jht310lyp"/><path class="x4ak42bic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:airplay-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jht310lyp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4h18v11H3Z");
}

.x4ak42bic {
  d: path("M6 16H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h2V5H4v9h2a1 1 0 0 1 0 2m11 5H7a1.002 1.002 0 0 1-.707-1.707l5-5a1 1 0 0 1 1.414 0l5 5A1 1 0 0 1 17 21m-7.586-2h5.172L12 16.414Z");
}

</style>
