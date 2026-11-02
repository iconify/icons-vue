<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lz_h6ew-s"/><path class="eriwvwsyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-close-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eriwvwsyp {
  d: path("m12 8.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 10l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 11.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 10L9.293 8.707a.999.999 0 1 1 1.414-1.414Z");
}

.lz_h6ew-s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 18H9c-.749 0-1.737.152-2.293.707l-1 1a1.71 1.71 0 0 1-1.498.485c-.461-.078-.866-.328-1.193-.655a3.4 3.4 0 0 1-.732-1.116A3.7 3.7 0 0 1 2 17V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5");
}

</style>
