<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m_nn0ob6f"/><path class="tsccvz_sm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:armchair-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m_nn0ob6f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11a3 3 0 1 1 6 0v1h6v-1a3 3 0 1 1 6 0v7a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

.tsccvz_sm {
  d: path("M5 4a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v5a1 1 0 0 1-2 0V5H7v4a1 1 0 0 1-2 0Zm2 16a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm12 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
