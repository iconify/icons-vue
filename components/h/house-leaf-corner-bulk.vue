<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fx2-nmbdp"/><path class="u6guqe5hw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-leaf-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fx2-nmbdp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.714 9H10a.997.997 0 0 0-1 1v11a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l4.397 3.847A1.001 1.001 0 0 1 17.714 9");
}

.u6guqe5hw {
  d: path("M20.996 13.909c.118 1.299.078 2.629-.265 3.893c-.279 1.023-.766 2.002-1.544 2.738c-1.395 1.317-3.27 1.428-4.99.678l-.49.489a.999.999 0 1 1-1.414-1.414l.489-.49c-.75-1.72-.639-3.595.678-4.99c.736-.778 1.715-1.265 2.738-1.544c1.264-.343 2.594-.383 3.893-.265c.48.044.86.424.905.904Zm-6.629 4.31l.926-.926a.999.999 0 1 1 1.414 1.414l-.926.926c1.658.317 2.614-.868 3.02-2.356c.205-.757.269-1.548.252-2.33c-.782-.017-1.573.047-2.33.252c-1.488.406-2.673 1.362-2.356 3.02");
}

</style>
