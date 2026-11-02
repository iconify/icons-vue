<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lz_h6ew-s"/><path class="s4_f-bc2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-dots-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lz_h6ew-s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 18H9c-.749 0-1.737.152-2.293.707l-1 1a1.71 1.71 0 0 1-1.498.485c-.461-.078-.866-.328-1.193-.655a3.4 3.4 0 0 1-.732-1.116A3.7 3.7 0 0 1 2 17V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5");
}

.s4_f-bc2n {
  d: path("M8.01 9a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2Z");
}

</style>
