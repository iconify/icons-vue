<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f3qqb6c9s"/><path class="ai_pf0b_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:files-bulk-sharp" /></template>
<style>
.ai_pf0b_p {
  d: path("M11 4a1 1 0 0 1 0-2h5c.265 0 .52.105.707.293l5 5A1 1 0 0 1 22 8v10a1 1 0 0 1-1 1h-4a1 1 0 0 1 0-2h3V9h-4a1 1 0 0 1-1-1V4Zm2.707 6.293A1 1 0 0 1 13 12H8a1 1 0 0 1-1-1V6a1 1 0 0 1 .994-1H8c.265 0 .52.105.707.293ZM17 5.414V7h1.586ZM9 10h1.586L9 8.414Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.f3qqb6c9s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 5c.265 0 .52.105.707.293l5 5A1 1 0 0 1 14 11v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1Zm0 6h4L8 7Z");
}

</style>
