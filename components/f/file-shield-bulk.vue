<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vn5g6zbpx"/><path class="hel2c8bhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-shield-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hel2c8bhg {
  d: path("M19 10h-4a3 3 0 0 1-3-3V3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10m-5-3a.997.997 0 0 0 1 1h1.586L14 5.414Zm2 7v1c0 1.087-.283 2.142-.969 3c-.676.844-1.629 1.417-2.584 1.894a1 1 0 0 1-.894 0C9.454 18.845 8.001 17.581 8 15v-1a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2m-2 0h-4v1c0 .345.035.694.14 1.023c.283.884 1.086 1.422 1.86 1.848c.774-.426 1.577-.964 1.86-1.848c.105-.329.14-.678.14-1.023Z");
}

.vn5g6zbpx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.707 8.293A1 1 0 0 1 20 9v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Z");
}

</style>
