<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h95s-svid"/><path class="yrdnxxrcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chess-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h95s-svid {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 22H8a3 3 0 0 1-.752-5.905L8.613 12H7a1 1 0 0 1-.894-.553l-1-2A1 1 0 0 1 5.4 8.2l3.423-2.568l-.772-2.316a1.001 1.001 0 0 1 1.265-1.265l3 1c1.666.556 2.921 1.688 3.703 3.252C16.744 7.753 17 9.391 17 11v5.171A3.001 3.001 0 0 1 16 22");
}

.yrdnxxrcz {
  d: path("M8 16h8a3 3 0 1 1 0 6H8a3 3 0 1 1 0-6m0 4h8a1 1 0 0 0 0-2H8a1 1 0 0 0 0 2");
}

</style>
