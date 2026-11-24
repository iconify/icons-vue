<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jer5s5b2c"/><path class="ceoaotbbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-edit-bulk-sharp" /></template>
<style>
.ceoaotbbw {
  d: path("M8 13v-2c0-.265.105-.52.293-.707l4-4a.997.997 0 0 1 1.414 0l2 2a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 11 14H9a1 1 0 0 1-1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.jer5s5b2c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 18H7.414l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1");
}

</style>
