<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ld40g7b6l"/><path class="nw82umbye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:billboard-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ld40g7b6l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

.nw82umbye {
  d: path("M7 6h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m0 4h6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2M6 21v-6a1 1 0 0 1 2 0v6a1 1 0 0 1-2 0m10 0v-6a1 1 0 0 1 2 0v6a1 1 0 0 1-2 0");
}

</style>
