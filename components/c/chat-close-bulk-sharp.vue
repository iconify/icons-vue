<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jer5s5b2c"/><path class="eriwvwsyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-close-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eriwvwsyp {
  d: path("m12 8.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 10l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 11.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 10L9.293 8.707a.999.999 0 1 1 1.414-1.414Z");
}

.jer5s5b2c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 18H7.414l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1");
}

</style>
