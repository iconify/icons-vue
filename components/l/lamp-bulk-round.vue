<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="epdzdybxt"/><path class="dlzwojbyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lamp-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dlzwojbyg {
  d: path("M13 11v5h1a3 3 0 1 1 0 6h-4a3 3 0 1 1 0-6h1v-5a1 1 0 0 1 2 0m-3 9h4a1 1 0 0 0 0-2h-4a1 1 0 0 0 0 2");
}

.epdzdybxt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 12H7c-1.265 0-2.164-1.076-2.167-2.298a2.5 2.5 0 0 1 .273-1.149l2-4C7.643 3.478 8.652 2.001 10 2h4c1.348.001 2.357 1.478 2.894 2.553l2 4c.181.356.274.75.273 1.149C19.164 10.924 18.265 12 17 12m-7 4h4a3 3 0 1 1 0 6h-4a3 3 0 1 1 0-6");
}

</style>
