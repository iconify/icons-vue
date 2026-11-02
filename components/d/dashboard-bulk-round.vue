<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p0d8_acbc"/><path class="xrvuenbxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dashboard-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p0d8_acbc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm10 8a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3Zm-7 1h2a3 3 0 1 1 0 6H6a3 3 0 1 1 0-6");
}

.xrvuenbxx {
  d: path("M16 3h2a3 3 0 1 1 0 6h-2a3 3 0 1 1 0-6m0 4h2a1 1 0 0 0 0-2h-2a1 1 0 0 0 0 2");
}

</style>
