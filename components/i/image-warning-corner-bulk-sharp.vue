<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vceg86bqq"/><path class="bh0qm40yr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-warning-corner-bulk-sharp" /></template>
<style>
.bh0qm40yr {
  d: path("M13 8a2 2 0 1 1 3.999-.001A2 2 0 0 1 13 8M2.293 16.293l6-6a1 1 0 0 1 1.414 0l2 2a.999.999 0 1 1-1.414 1.414L9 12.414l-5.293 5.293a.999.999 0 1 1-1.414-1.414M19 15v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0m-1 5h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.vceg86bqq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-9v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

</style>
