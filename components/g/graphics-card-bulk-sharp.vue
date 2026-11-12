<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mv1ba1f6w"/><path class="d3184lwwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graphics-card-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d3184lwwo {
  d: path("M2 21V3a1 1 0 0 1 2 0v18a1 1 0 0 1-2 0m3-10a3 3 0 1 1 6 0a3 3 0 0 1-6 0m8 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m8 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0M6 21v-4a1 1 0 0 1 2 0v3h8v-3a1 1 0 0 1 2 0v4a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1");
}

.mv1ba1f6w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
