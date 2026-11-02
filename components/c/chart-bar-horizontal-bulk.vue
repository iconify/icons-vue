<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jfv2lnc4c"/><path class="bbikbkuko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-horizontal-bulk" /></template>
<style>
.bbikbkuko {
  d: path("M13 8a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm3 6a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.jfv2lnc4c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 2h7a3 3 0 0 1 0 6H4a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1M3 14v-4a1 1 0 0 1 1-1h14a3 3 0 1 1 0 6H4a1 1 0 0 1-1-1m11 8H4a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h10a3 3 0 0 1 0 6");
}

</style>
