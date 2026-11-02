<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qnvpo9bhd"/><path class="gz1qhtbpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caravan-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gz1qhtbpb {
  d: path("M21 14a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2ZM7.236 16.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.qnvpo9bhd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 4a5 5 0 0 1 5 5v7a3 3 0 0 1-3 3h-2.171a3 3 0 0 1-5.658 0H5a3 3 0 0 1-3-3V9a5 5 0 0 1 5-5Zm-7 6v2a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2v-2a2 2 0 0 0-2-2H8a2 2 0 0 0-2 2m3.293 8.707l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0-.002-1.412l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 .002 1.412");
}

</style>
