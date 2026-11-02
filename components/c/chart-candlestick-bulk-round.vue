<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hkbigu5ks"/><path class="te_1idb1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-candlestick-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hkbigu5ks {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 7a3 3 0 1 1 6 0v3a3 3 0 1 1-6 0ZM2 17a3 3 0 1 1 6 0v1a3 3 0 1 1-6 0Zm14 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

.te_1idb1x {
  d: path("M11 5V3a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0M4 15v-3a1 1 0 0 1 2 0v3a1 1 0 0 1-2 0m7 0v-3a1 1 0 0 1 2 0v3a1 1 0 0 1-2 0m7 0v-3a1 1 0 0 1 2 0v3a1 1 0 0 1-2 0m0 6v-2a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0M4 20a1 1 0 0 1 2 0v1a1 1 0 0 1-2 0Z");
}

</style>
