<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dovihdc4k"/><path class="oyp-qib8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-subtract-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dovihdc4k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 2a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-5v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Z");
}

.oyp-qib8o {
  d: path("M19 8h2a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0v-3h-1a1 1 0 0 1 0-2m2 14h-4a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0v4a1 1 0 0 1-1 1M8 19a1 1 0 0 1 2 0v1h3a1 1 0 0 1 0 2H9a1 1 0 0 1-1-1Z");
}

</style>
