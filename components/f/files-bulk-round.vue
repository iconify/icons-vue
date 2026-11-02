<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ymxzlpbfu"/><path class="x1tr1zh4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:files-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.x1tr1zh4h {
  d: path("M11 4a1 1 0 0 1 0-2h5c.265 0 .52.105.707.293l5 5A1 1 0 0 1 22 8v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 19a1 1 0 0 1 0-2c.193 0 .389-.018.578-.055h.001A3 3 0 0 0 20 14V9h-3a2 2 0 0 1-2-1.999V4Zm2.707 6.293A1 1 0 0 1 13 12H9a2 2 0 0 1-2-2V6a1 1 0 0 1 .994-1H8c.265 0 .52.105.707.293ZM17 5.414V7h1.586ZM9 10h1.586L9 8.414Z");
}

.ymxzlpbfu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.707 10.293A1 1 0 0 1 14 11v6a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5v-7a5 5 0 0 1 5-5h1c.265 0 .52.105.707.293ZM8 10a1 1 0 0 0 1 1h3L8 7Z");
}

</style>
