<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wuptzwomv"/><path class="mhbiio4dt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-lock-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mhbiio4dt {
  d: path("M14 15a3 3 0 1 1 6 0a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2m2 0h2a1 1 0 0 0-2 0");
}

.wuptzwomv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.707 3.293L12.414 5H19a3 3 0 0 1 3 3a1 1 0 0 1-1 1H10a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293");
}

</style>
