<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wfnnwnbmv"/><path class="x773wi8ow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-check-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wfnnwnbmv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 13v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h6a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779c.52 1.556 1.603 2.735 3.003 3.551c1.093.638 2.364 1.031 3.638.985a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13");
}

.x773wi8ow {
  d: path("m17 6.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414ZM4.293 4.879l4.414 4.414c.315.315.825.707 1.293.707h3a1 1 0 0 1 0 2h-3c-1.039 0-1.991-.577-2.707-1.293L2.879 6.293a.999.999 0 1 1 1.414-1.414");
}

</style>
