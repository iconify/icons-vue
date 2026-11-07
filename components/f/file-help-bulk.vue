<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vn5g6zbpx"/><path class="fyfejo_-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-help-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fyfejo_-w {
  d: path("M19 10h-4a3 3 0 0 1-3-3V3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10m-5-3a.997.997 0 0 0 1 1h1.586L14 5.414Zm-5.764 4.832A3 3 0 1 1 11 16a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 10 13a1 1 0 0 1-2 0a3 3 0 0 1 .236-1.168M11.01 17a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2Z");
}

.vn5g6zbpx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.707 8.293A1 1 0 0 1 20 9v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Z");
}

</style>
