<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="slcc5xbme"/><path class="wt3eodyvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.slcc5xbme {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 5a3 3 0 0 1 3 3v8a6 6 0 0 1-6 6h-4c-1.039 0-1.992-.578-2.707-1.293l-6-6c-.945-.945-1.233-2.271-.653-3.492c.163-.343.384-.655.653-.922c.267-.269.579-.49.922-.653a3 3 0 0 1 2.364-.099c.425.167.806.43 1.128.752l.293.293V7a3 3 0 0 1 4.105-2.79A3.001 3.001 0 0 1 18 5Z");
}

.wt3eodyvz {
  d: path("M14 12a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0Z");
}

</style>
