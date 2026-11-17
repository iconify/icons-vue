<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="om9_j4m1l"/><path class="x4gl8vg1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:light-switch-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.om9_j4m1l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 2h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5m2 7v6a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1");
}

.x4gl8vg1l {
  d: path("M10 6h4a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3m5 5V9a.997.997 0 0 0-1-1h-4a.997.997 0 0 0-1 1v2Zm-6 2v2a.997.997 0 0 0 1 1h4a.997.997 0 0 0 1-1v-2Z");
}

</style>
