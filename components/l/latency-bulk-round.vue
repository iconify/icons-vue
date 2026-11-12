<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oqiew-cux"/><path class="wwp0aszmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:latency-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oqiew-cux {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 14a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

.wwp0aszmp {
  d: path("M12 2h3a1 1 0 0 1 0 2h-2v3a1 1 0 0 1-2 0V4H9a1 1 0 0 1 0-2ZM9.279 13l.772-2.316a1 1 0 0 1 1.898 0L13 13.838l.051-.154A1 1 0 0 1 14 13h2a1 1 0 0 1 0 2h-1.279l-.772 2.316a1 1 0 0 1-1.898 0L11 14.162l-.051.154A1 1 0 0 1 10 15H8a1 1 0 0 1 0-2Z");
}

</style>
