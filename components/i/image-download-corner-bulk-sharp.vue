<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vceg86bqq"/><path class="pshk5_48u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-download-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pshk5_48u {
  d: path("M13 8a2 2 0 1 1 3.999-.001A2 2 0 0 1 13 8M2.293 16.293l6-6a1 1 0 0 1 1.414 0l2 2a.999.999 0 1 1-1.414 1.414L9 12.414l-5.293 5.293a.999.999 0 1 1-1.414-1.414m15 5.414l-3-3a1 1 0 0 1 1.414-1.414L17 18.586V15a1 1 0 0 1 2 0v3.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0");
}

.vceg86bqq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-9v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

</style>
