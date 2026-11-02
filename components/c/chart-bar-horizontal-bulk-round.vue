<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hc3-1abqr"/><path class="bbikbkuko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-horizontal-bulk-round" /></template>
<style>
.bbikbkuko {
  d: path("M13 8a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm3 6a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hc3-1abqr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 2a3 3 0 0 1 1.983 5.251l-.003.003A2.98 2.98 0 0 1 11 8H4a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1ZM3 14v-4a1 1 0 0 1 1-1h14a3 3 0 1 1 0 6H4a1 1 0 0 1-1-1m11 8H4a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h10a3 3 0 0 1 0 6");
}

</style>
