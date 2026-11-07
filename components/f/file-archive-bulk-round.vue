<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a5n5ajdgx"/><path class="iehgwlb-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-archive-bulk-round" /></template>
<style>
.a5n5ajdgx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v8c0 1.33-.522 2.597-1.464 3.536A5 5 0 0 1 15 22a1 1 0 0 1-1-1v-3a4 4 0 0 0-8-.003V18a1 1 0 0 1-2 0Zm9 0a2 2 0 0 0 2 2h3l-5-5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.iehgwlb-z {
  d: path("M19.707 8.293A1 1 0 0 1 19 10h-4a3 3 0 0 1-3-3V4H9a3 3 0 0 0-3 3v14a1 1 0 0 1-2 0V7a5 5 0 0 1 5-5h4a1 1 0 0 1 .698.284l.009.008v.001ZM10.01 5a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm3.99.414V7a.997.997 0 0 0 1 1h1.586ZM8.01 7a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm2 2a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm-2 2a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2ZM13 18v2a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-2a3 3 0 0 1 3-3h.001A3 3 0 0 1 13 18m-4-.001V20h2v-2a1 1 0 0 0-2-.001");
}

</style>
