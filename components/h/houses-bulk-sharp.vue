<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zypkq93wv"/><path class="g1gc0ebvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:houses-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g1gc0ebvy {
  d: path("M13.01 6a1 1 0 0 1 0 2H13a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2ZM2 21v-7.625c0-.288.124-.563.341-.753l5-4.375c.378-.329.94-.329 1.318 0l5 4.375c.217.19.341.465.341.753V21a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m10-1v-6.171l-4-3.5l-4 3.5V20Zm5.01-10a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

.zypkq93wv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 2h12a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1v-7.171l-3.659-3.201A1 1 0 0 1 8 9.875V3a1 1 0 0 1 1-1");
}

</style>
