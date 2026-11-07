<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="okjsc7yvd"/><path class="i_3lyyc1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-quote-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i_3lyyc1n {
  d: path("M10 7a1 1 0 0 1 1 1v2c0 .265-.105.52-.293.707l-2 2a.999.999 0 1 1-1.414-1.414L9 9.586V9H8a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 1 1v2c0 .265-.105.52-.293.707l-2 2a.999.999 0 1 1-1.414-1.414L15 9.586V9h-1a1 1 0 0 1 0-2Z");
}

.okjsc7yvd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 18H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3");
}

</style>
