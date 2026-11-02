<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="izm_7_4_y"/><path class="co47idbtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bus-bulk-sharp" /></template>
<style>
.co47idbtl {
  d: path("M9 5h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2M8 15h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m8 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.izm_7_4_y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 19V3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1h-1v1a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1h-4v1a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-1H5a1 1 0 0 1-1-1M6 4v8h12V4Z");
}

</style>
