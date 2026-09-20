<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="tqayn_6pe"/><path class="g0jkmwbam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chats-circle-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g0jkmwbam {
  d: path("M232.07 186.76a80 80 0 0 0-62.5-114.17a80 80 0 1 0-145.64 66.17l-7.27 24.71a16 16 0 0 0 19.87 19.87l24.71-7.27a80.4 80.4 0 0 0 25.18 7.35a80 80 0 0 0 108.34 40.65l24.71 7.27a16 16 0 0 0 19.87-19.86ZM62 159.5a8.3 8.3 0 0 0-2.26.32L32 168l8.17-27.76a8 8 0 0 0-.63-6A64 64 0 1 1 65.8 160.5a8 8 0 0 0-3.8-1m153.79 28.73L224 216l-27.76-8.17a8 8 0 0 0-6 .63a64.05 64.05 0 0 1-85.87-24.88a79.93 79.93 0 0 0 70.33-93.87a64 64 0 0 1 41.75 92.48a8 8 0 0 0-.63 6.04Z");
}

.tqayn_6pe {
  d: path("M231.66 213.73a8 8 0 0 1-9.93 9.93L194 215.5a72.05 72.05 0 0 1-101.94-39.61c1.31.07 2.62.11 3.94.11a72 72 0 0 0 67.93-95.88A72 72 0 0 1 223.5 186Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
