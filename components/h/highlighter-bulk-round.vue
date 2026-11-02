<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zgmc0xmap"/><path class="yjoc9gb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:highlighter-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.yjoc9gb0p {
  d: path("M4.707 16.707C4.39 17.024 4 17.532 4 18v1h3.001c.467 0 .974-.389 1.292-.707l3-3a.999.999 0 1 1 1.414 1.414l-3 3C8.992 20.422 8.038 21 7 21H4a2 2 0 0 1-2-2v-1c0-1.039.577-1.992 1.293-2.707l4-4a.999.999 0 1 1 1.414 1.414Z");
}

.zgmc0xmap {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m6.293 10.293l4-4a5.243 5.243 0 0 1 7.414 7.414l-4 4a1 1 0 0 1-1.414 0l-6-6a.997.997 0 0 1 0-1.414");
}

</style>
