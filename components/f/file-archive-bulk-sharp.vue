<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ls04w_7ye"/><path class="le0apwb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-archive-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.le0apwb7f {
  d: path("m13.707 2.293l6 6A1 1 0 0 1 19 10h-6a1 1 0 0 1-1-1V3a1.002 1.002 0 0 1 1.707-.707M14 5.414V8h2.586ZM10.01 5a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm-2 2a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm2 2a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm-2 2a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2ZM13 18v2a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-2a3 3 0 1 1 6 0m-4 0v2h2v-2a1 1 0 0 0-2 0");
}

.ls04w_7ye {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 21V3a1 1 0 0 1 1-1h8c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-3a4 4 0 0 0-8-.003V21a1 1 0 0 1-2 0m9-17v5h5Z");
}

</style>
