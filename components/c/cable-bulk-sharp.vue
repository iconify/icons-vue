<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j_6duab6b"/><path class="w3h_obbav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j_6duab6b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1Zm10 10a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Z");
}

.w3h_obbav {
  d: path("M6 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm7 6a1 1 0 0 1 1 1v3a1 1 0 0 1-2 0v-2H7a1 1 0 0 1-1-1V9a1 1 0 0 1 2 0v2Zm-1 10a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
