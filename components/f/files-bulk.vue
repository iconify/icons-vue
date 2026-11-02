<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="px2f8bd-l"/><path class="kxne7h4zr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:files-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kxne7h4zr {
  d: path("M11 4a1 1 0 0 1 0-2h5c.265 0 .52.105.707.293l5 5A1 1 0 0 1 22 8v8a3.004 3.004 0 0 1-3 3h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1V9h-3a2 2 0 0 1-2-1.999V4Zm2.707 6.293A1 1 0 0 1 13 12H9a2 2 0 0 1-2-2V6a1 1 0 0 1 .994-1H8c.265 0 .52.105.707.293ZM17 5.414V7h1.586ZM9 10h1.586L9 8.414Z");
}

.px2f8bd-l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.707 10.293A1 1 0 0 1 14 11v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3h3c.265 0 .52.105.707.293ZM8 10a1 1 0 0 0 1 1h3L8 7Z");
}

</style>
