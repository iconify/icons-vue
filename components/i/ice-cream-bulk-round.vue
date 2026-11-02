<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="npkifbcpj"/><path class="ldkxcoxeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ice-cream-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ldkxcoxeq {
  d: path("M7 11h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

.npkifbcpj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.059 7.151a6.001 6.001 0 0 1 11.882 0a3 3 0 0 1-.317 5.784l-4.75 8.551a1 1 0 0 1-1.748 0l-4.75-8.551a3 3 0 0 1-.317-5.784");
}

</style>
