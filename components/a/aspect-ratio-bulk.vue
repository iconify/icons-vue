<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="trdjr4bpx"/><path class="bls7-mbul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:aspect-ratio-bulk" /></template>
<style>
.bls7-mbul {
  d: path("M6 12v-2a2 2 0 0 1 2-2h2a1 1 0 0 1 0 2H8v2a1 1 0 0 1-2 0m12 2a2 2 0 0 1-2 2h-2a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.trdjr4bpx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
