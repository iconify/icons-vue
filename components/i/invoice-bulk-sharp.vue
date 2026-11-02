<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y7hl_mbmd"/><path class="my84ncc_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:invoice-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.my84ncc_h {
  d: path("M19 10h-6a1 1 0 0 1-1-1V3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10m-5-2h2.586L14 5.414Zm-4-2a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm5 8H9a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2m0 2a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2Z");
}

.y7hl_mbmd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 7h5l-5-5Z");
}

</style>
