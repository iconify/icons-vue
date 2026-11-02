<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uub5b9-9u"/><path class="i1vt_qbof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-bitcoin-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i1vt_qbof {
  d: path("M7 4h6a4 4 0 0 1 4 4v1c0 .943-.329 1.851-.936 2.572A4 4 0 0 1 18 15v1a4 4 0 0 1-4 4H7a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1m1 9v5h6a2 2 0 0 0 2-2v-1a2 2 0 0 0-2-2Zm0-2h5a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2H8Z");
}

.uub5b9-9u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM8 21a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
