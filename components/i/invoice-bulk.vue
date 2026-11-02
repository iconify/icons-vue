<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vn5g6zbpx"/><path class="adfhx4bcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:invoice-bulk" /></template>
<style>
.adfhx4bcn {
  d: path("M19 10h-4a3 3 0 0 1-3-3V3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10m-5-3a.997.997 0 0 0 1 1h1.586L14 5.414Zm-4-1a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm5 8H9a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2m0 2a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.vn5g6zbpx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.707 8.293A1 1 0 0 1 20 9v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Z");
}

</style>
