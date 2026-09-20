<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="rfj05cbvb"/><path class="m361shp2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bulldozer-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m361shp2z {
  d: path("M248 200h-8a8 8 0 0 1-8-8v-32a8 8 0 0 1 8-8h8a8 8 0 0 0 0-16h-8a24 24 0 0 0-24 24v8h-16.8a40.09 40.09 0 0 0-33.71-31.61l-36.05-86.54A16 16 0 0 0 114.67 40H24A16 16 0 0 0 8 56v96a40 40 0 0 0 32 64h120a40.07 40.07 0 0 0 39.2-32H216v8a24 24 0 0 0 24 24h8a8 8 0 0 0 0-16m-100-64H64V56h50.67ZM48 56v80h-8a39.7 39.7 0 0 0-16 3.35V56Zm112 144H40a24 24 0 0 1 0-48h120a24 24 0 0 1 0 48m8-24a8 8 0 0 1-8 8H40a8 8 0 0 1 0-16h120a8 8 0 0 1 8 8");
}

.rfj05cbvb {
  d: path("M192 176a32 32 0 0 1-32 32H40a32 32 0 0 1-32-32a32 32 0 0 1 32-32h120a32 32 0 0 1 32 32");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
