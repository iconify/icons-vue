<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bq6oz7adf"/><path class="lirtwccvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-minus-bulk-round" /></template>
<style>
.bq6oz7adf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 22H8a5 5 0 0 1-5-5v-4c0-1.317.335-2.748 1.293-3.707l4-4a5.243 5.243 0 0 1 7.414 0l4 4C20.665 10.252 21 11.683 21 13v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lirtwccvs {
  d: path("M9 13h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
