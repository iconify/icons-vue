<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d-y0bfm-u"/><path class="dn9_vjbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d-y0bfm-u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 17.757L6.243 2H21a1 1 0 0 1 1 1ZM2.293 2.293l19.414 19.414A1 1 0 0 1 21 22H3a1 1 0 0 1-1-1V3c0-.265.105-.52.293-.707");
}

.dn9_vjbnt {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414L10 11.414l-6.293 6.293a.999.999 0 1 1-1.414-1.414L8.586 10L1.293 2.707a.999.999 0 1 1 1.414-1.414M14 8a2 2 0 1 1 3.999-.001A2 2 0 0 1 14 8");
}

</style>
