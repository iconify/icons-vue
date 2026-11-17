<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r2leyqb6j"/><path class="bm1kp1bis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:blinds-bulk-sharp" /></template>
<style>
.bm1kp1bis {
  d: path("M3 2h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m16 4a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm-6 5v1.171a3 3 0 1 1-2 0V15a1 1 0 0 1 2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.r2leyqb6j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

</style>
