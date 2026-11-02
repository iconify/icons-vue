<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="okezpobnk"/><path class="mk_k2ibmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cookie-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mk_k2ibmk {
  d: path("M4.01 2a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2ZM8 2h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2M3.01 6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2ZM16 9h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2m-4.99 2a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2ZM15 14h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-4.99 2a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Z");
}

.okezpobnk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12a1 1 0 0 1 1.11-.994A3.526 3.526 0 0 0 7.006 7.89c.052-.465.419-.832.884-.884a3.52 3.52 0 0 0 2.365-1.302a3.52 3.52 0 0 0 .751-2.594A1 1 0 0 1 12 2");
}

</style>
