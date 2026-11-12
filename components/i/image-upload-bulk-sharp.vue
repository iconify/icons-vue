<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="td1bzxb2d"/><path class="mmzsd_xmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-upload-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mmzsd_xmr {
  d: path("M17.293 9.707L16 8.414V12a1 1 0 0 1-2 0V8.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414m-15 6.586l4-4a1 1 0 0 1 1.414 0l8 8a.999.999 0 1 1-1.414 1.414L7 14.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414");
}

.td1bzxb2d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

</style>
