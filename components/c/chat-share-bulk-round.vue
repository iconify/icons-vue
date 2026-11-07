<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lz_h6ew-s"/><path class="zqfl_7ojq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-share-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lz_h6ew-s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 18H9c-.749 0-1.737.152-2.293.707l-1 1a1.71 1.71 0 0 1-1.498.485c-.461-.078-.866-.328-1.193-.655a3.4 3.4 0 0 1-.732-1.116A3.7 3.7 0 0 1 2 17V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5");
}

.zqfl_7ojq {
  d: path("M16.707 9.293a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L13.586 11H11a2 2 0 0 0-2 2a1 1 0 0 1-2 0c0-1.064.418-2.078 1.172-2.828A3.98 3.98 0 0 1 11 9h2.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414Z");
}

</style>
