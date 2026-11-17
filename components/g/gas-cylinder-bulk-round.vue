<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e-vllor_j"/><path class="d7hvob1ts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gas-cylinder-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d7hvob1ts {
  d: path("M7 5a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V5a.997.997 0 0 0-1-1h-4a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0Zm13 7a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2ZM9 20h6v-1a1 1 0 0 1 2 0v2a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0Z");
}

.e-vllor_j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 2h4a3 3 0 0 1 2.806 4.064A5.005 5.005 0 0 1 21 11v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 20H8a5 5 0 0 1-5-5v-4a5.005 5.005 0 0 1 4.194-4.936A3.002 3.002 0 0 1 10 2M9 4v2h6V4Z");
}

</style>
