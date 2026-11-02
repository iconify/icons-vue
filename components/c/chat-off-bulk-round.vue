<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vidpmis6l"/><path class="lk3mfzb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lk3mfzb5t {
  d: path("M2.293 2.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

.vidpmis6l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.381 15.138L7.243 2H17a5 5 0 0 1 5 5v6a5 5 0 0 1-.897 2.86ZM3.999 2.999l14.704 14.704A5 5 0 0 1 17 18H9c-.749 0-1.737.152-2.293.707l-1 1a1.71 1.71 0 0 1-1.498.485c-.461-.078-.866-.328-1.193-.655a3.4 3.4 0 0 1-.732-1.116A3.7 3.7 0 0 1 2 17V7c0-1.576.737-3.057 1.999-4.001");
}

</style>
