<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="adyr2b36g"/><path class="kfye3lbll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ceiling-light-bulk-round" /></template>
<style>
.adyr2b36g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 17H3a1 1 0 0 1-1-1C2 10.477 6.477 6 12 6s10 4.477 10 10a1 1 0 0 1-1 1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kfye3lbll {
  d: path("M13 7a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-5 8h13a1 1 0 0 1 0 2h-4.099a5.003 5.003 0 0 1-9.802 0H3a1 1 0 0 1 0-2Zm1.17 2a3.002 3.002 0 0 0 5.66 0Z");
}

</style>
