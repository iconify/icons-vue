<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ai237mb3y"/><path class="w5_x33b7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-solar-panel-bulk-sharp" /></template>
<style>
.ai237mb3y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.659 9.247c.217.19.341.465.341.753v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.w5_x33b7d {
  d: path("M8 19a1 1 0 0 1-.992-1.124l1-8A1 1 0 0 1 9 9h6a1 1 0 0 1 .992.876l1 8A.997.997 0 0 1 16 19Zm3-8H9.883l-.25 2H11Zm0 4H9.383l-.25 2H11Zm2 2h1.867l-.25-2H13Zm1.367-4l-.25-2H13v2Z");
}

</style>
