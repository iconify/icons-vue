<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g7cj19b0u"/><path class="lfpu221si"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-edit-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g7cj19b0u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 9H10v10a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5");
}

.lfpu221si {
  d: path("M3 8h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m9.293 9.293l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 16 22h-3a1 1 0 0 1-1-1v-3c0-.265.105-.52.293-.707");
}

</style>
