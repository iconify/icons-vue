<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jer5s5b2c"/><path class="i_3lyyc1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-quote-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i_3lyyc1n {
  d: path("M10 7a1 1 0 0 1 1 1v2c0 .265-.105.52-.293.707l-2 2a.999.999 0 1 1-1.414-1.414L9 9.586V9H8a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 1 1v2c0 .265-.105.52-.293.707l-2 2a.999.999 0 1 1-1.414-1.414L15 9.586V9h-1a1 1 0 0 1 0-2Z");
}

.jer5s5b2c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 18H7.414l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1");
}

</style>
