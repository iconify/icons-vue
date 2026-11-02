<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uz8p_-bfe"/><path class="p84_zz_5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-plus-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p84_zz_5b {
  d: path("M15 11v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2V7a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2ZM4 20h11a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V9a1 1 0 0 1 2 0Z");
}

.uz8p_-bfe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Z");
}

</style>
