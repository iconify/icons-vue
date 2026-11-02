<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vab3u-aec"/><path class="qionwobvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qionwobvx {
  d: path("M2 16a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm2 1v2h16v-2Z");
}

.vab3u-aec {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

</style>
