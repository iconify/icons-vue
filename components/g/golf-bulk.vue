<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bnj9fsb8d"/><path class="j_phh1bkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:golf-bulk" /></template>
<style>
.bnj9fsb8d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 5c0-1.265 1.076-2.164 2.298-2.167c.399-.001.793.092 1.149.273l4 2a2.116 2.116 0 0 1 0 3.788l-5.999 3A1 1 0 0 1 9 11Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.j_phh1bkl {
  d: path("M11 17a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Zm-4 2c0 .049.049.099.078.133c.144.17.344.288.541.387c1.058.529 2.591.586 3.731.344c.486-.102 1.237-.335 1.572-.731c.029-.034.078-.084.078-.133a1 1 0 0 1 2 0c0 .528-.21 1.022-.551 1.425c-1.779 2.102-7.121 2.1-8.898 0C5.21 20.021 5 19.53 5 19a1 1 0 0 1 2 0");
}

</style>
