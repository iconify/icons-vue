<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wfnnwnbmv"/><path class="mf3jc4oyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-close-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mf3jc4oyd {
  d: path("m18 4.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L19.414 6l1.293 1.293a.999.999 0 1 1-1.414 1.414L18 7.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L16.586 6l-1.293-1.293a.999.999 0 1 1 1.414-1.414Zm-13.707.293l4.414 4.414c.315.315.825.707 1.293.707h3a1 1 0 0 1 0 2h-3c-1.039 0-1.991-.577-2.707-1.293L2.879 6.293a.999.999 0 1 1 1.414-1.414");
}

.wfnnwnbmv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 13v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h6a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779c.52 1.556 1.603 2.735 3.003 3.551c1.093.638 2.364 1.031 3.638.985a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13");
}

</style>
