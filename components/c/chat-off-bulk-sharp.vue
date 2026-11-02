<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mgw-sxbnl"/><path class="lk3mfzb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lk3mfzb5t {
  d: path("M2.293 2.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

.mgw-sxbnl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3 2l16 16H7.414l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1m19 14.757L7.243 2H21a1 1 0 0 1 1 1Z");
}

</style>
