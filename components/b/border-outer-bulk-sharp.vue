<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bpp7y5g_r"/><path class="pbezt3bzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:border-outer-bulk-sharp" /></template>
<style>
.bpp7y5g_r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.pbezt3bzr {
  d: path("M12.01 6a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm-5 5a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2ZM12 11h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m5.01 0a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2ZM12 16h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
