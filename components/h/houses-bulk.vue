<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ep_61j5jv"/><path class="pg47_6yqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:houses-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ep_61j5jv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 22h-8a1 1 0 0 1-1-1v-6.717a1 1 0 0 0-.341-.753l-3.318-2.902A1 1 0 0 1 8 9.875V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v16a1 1 0 0 1-1 1");
}

.pg47_6yqz {
  d: path("M13.01 6a1 1 0 0 1 0 2H13a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2ZM2 21v-6.717c0-.866.373-1.689 1.024-2.258l3-2.625a3 3 0 0 1 3.952 0l3 2.625A3 3 0 0 1 14 14.283V21a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m10-1v-5.717a1 1 0 0 0-.341-.753l-3-2.625c-.378-.33-.94-.33-1.318 0l-3 2.625a1 1 0 0 0-.341.753V20Zm5.01-10a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

</style>
