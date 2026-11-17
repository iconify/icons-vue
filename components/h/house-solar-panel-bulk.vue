<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k0z9u4bez"/><path class="w5_x33b7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-solar-panel-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k0z9u4bez {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 22H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l6 5.25A3 3 0 0 1 21 10.908V19a3 3 0 0 1-3 3");
}

.w5_x33b7d {
  d: path("M8 19a1 1 0 0 1-.992-1.124l1-8A1 1 0 0 1 9 9h6a1 1 0 0 1 .992.876l1 8A.997.997 0 0 1 16 19Zm3-8H9.883l-.25 2H11Zm0 4H9.383l-.25 2H11Zm2 2h1.867l-.25-2H13Zm1.367-4l-.25-2H13v2Z");
}

</style>
