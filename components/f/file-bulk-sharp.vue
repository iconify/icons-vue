<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y7hl_mbmd"/><path class="p3ipkqjov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p3ipkqjov {
  d: path("M19.707 8.293A1 1 0 0 1 19 10h-6a1 1 0 0 1-1-1V3a1 1 0 0 1 1.698-.716l.009.008v.001ZM14 5.414V8h2.586Z");
}

.y7hl_mbmd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 7h5l-5-5Z");
}

</style>
