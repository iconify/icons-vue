<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vh2hsbcgb"/><path class="nrl7b1rkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eyedropper-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nrl7b1rkc {
  d: path("M8.293 8.707a.999.999 0 1 1 1.414-1.414l.293.293l3.293-3.293a4.536 4.536 0 0 1 6.414 6.414L16.414 14l.293.293a.999.999 0 1 1-1.414 1.414ZM15 12.586l3.293-3.293a2.536 2.536 0 0 0-3.586-3.586L11.414 9Z");
}

.vh2hsbcgb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.293 9.293a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5a1 1 0 0 1-.336.221l-5 2a.998.998 0 0 1-1.299-1.299l2-5a1 1 0 0 1 .221-.336Z");
}

</style>
