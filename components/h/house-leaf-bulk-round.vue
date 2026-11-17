<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o3cwdvb-i"/><path class="m7_w-vnvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-leaf-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m7_w-vnvz {
  d: path("M15.996 9.909c.118 1.299.078 2.629-.265 3.893c-.279 1.023-.766 2.002-1.544 2.738c-1.395 1.317-3.27 1.428-4.99.678l-.49.489a.999.999 0 1 1-1.414-1.414l.489-.49c-.75-1.72-.639-3.595.678-4.99c.736-.778 1.715-1.265 2.738-1.544c1.264-.343 2.594-.383 3.893-.265c.48.044.86.424.905.904Zm-5.215 5.724c1.658.317 2.614-.868 3.02-2.356c.205-.757.269-1.548.252-2.33c-.782-.017-1.573.047-2.33.252c-1.488.406-2.673 1.362-2.356 3.02l.926-.926a.999.999 0 1 1 1.414 1.414Z");
}

.o3cwdvb-i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 22H8a5 5 0 0 1-5-5v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l4 3.5A5 5 0 0 1 21 11.815V17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22");
}

</style>
