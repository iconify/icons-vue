<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="lzc9bib4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-angry-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lzc9bib4a {
  d: path("M10.447 9.106a1 1 0 1 1-.894 1.788l-2-1a1 1 0 1 1 .894-1.788Zm4 1.788a1 1 0 1 1-.894-1.788l2-1a1 1 0 1 1 .894 1.788Zm-7.154 3.399c2.6-2.6 6.814-2.6 9.414 0a.997.997 0 0 1 0 1.414a1 1 0 0 1-1.414 0A4.64 4.64 0 0 0 12 14.343a4.64 4.64 0 0 0-3.293 1.364a.999.999 0 1 1-1.414-1.414");
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
