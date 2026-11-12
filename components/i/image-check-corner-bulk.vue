<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b1f_3v3sz"/><path class="ipalg36uc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-check-corner-bulk" /></template>
<style>
.b1f_3v3sz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 12h-8a.997.997 0 0 0-1 1v8a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v6a1 1 0 0 1-1 1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ipalg36uc {
  d: path("M13 8a2 2 0 1 1 3.999-.001A2 2 0 0 1 13 8M2.293 16.293l5-5a2.415 2.415 0 0 1 3.414 0l1 1a.999.999 0 1 1-1.414 1.414l-1-1a.415.415 0 0 0-.586 0l-5 5a.999.999 0 1 1-1.414-1.414m13.414 1L17 18.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a1 1 0 0 1 1.414-1.414");
}

</style>
