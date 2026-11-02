<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tevqkpmlv"/><path class="a89hm0bcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:factory-bulk-sharp" /></template>
<style>
.a89hm0bcg {
  d: path("M8 15h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2m5 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.tevqkpmlv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 21V3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v7.234l3.486-2.091A.997.997 0 0 1 15 9v1.234l3.486-2.091A.997.997 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1");
}

</style>
