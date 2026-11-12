<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bq6oz7adf"/><path class="zm5_mabok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-percent-bulk-round" /></template>
<style>
.bq6oz7adf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 22H8a5 5 0 0 1-5-5v-4c0-1.317.335-2.748 1.293-3.707l4-4a5.243 5.243 0 0 1 7.414 0l4 4C20.665 10.252 21 11.683 21 13v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22");
}

.cuyn6tgcc {
  fill: currentColor;
}

.zm5_mabok {
  d: path("M10.707 17.707a.999.999 0 1 1-1.414-1.414l4-4a.999.999 0 1 1 1.414 1.414ZM10.01 12a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm4 4a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2Z");
}

</style>
