<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o_7-63buy"/><path class="kprizacfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-vertical-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kprizacfi {
  d: path("M14 8a1 1 0 0 1 2 0v12a1 1 0 0 1-2 0Zm-6 3a1 1 0 0 1 2 0v9a1 1 0 0 1-2 0Z");
}

.o_7-63buy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 3h4a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m7 4h4a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1M3 10h4a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1");
}

</style>
