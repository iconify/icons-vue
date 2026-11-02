<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lp58_lf9s"/><path class="kqrliobak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-triangle-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kqrliobak {
  d: path("M7 21a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Z");
}

.lp58_lf9s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 5c0-1.265 1.076-2.164 2.298-2.167c.399-.001.793.092 1.149.273l8 4a2.116 2.116 0 0 1 0 3.788l-10 5A1 1 0 0 1 5 15Z");
}

</style>
