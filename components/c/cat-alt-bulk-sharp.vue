<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lzbnldvse"/><path class="e_n7rl6qx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cat-alt-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e_n7rl6qx {
  d: path("M9 10h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2M2.757 13.97a1 1 0 0 1 .486-1.94l4 1a1 1 0 0 1-.486 1.94Zm18.486 0l-4 1a1 1 0 0 1-.486-1.94l4-1a1 1 0 0 1 .486 1.94M11 13h2a1.002 1.002 0 0 1 .707 1.707l-1 1a1 1 0 0 1-1.414 0l-1-1A1 1 0 0 1 11 13m-7.804 5.981a1.001 1.001 0 0 1-.392-1.962l5-1a1.001 1.001 0 0 1 .392 1.962Zm17.608 0l-5-1a1.001 1.001 0 0 1 .392-1.962l5 1a1.001 1.001 0 0 1-.392 1.962");
}

.lzbnldvse {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 7.849V3a1 1 0 0 1 1.243-.97a7.3 7.3 0 0 1 2.875 1.431c.512.415.968.896 1.353 1.431a10 10 0 0 1 3.058 0a7.4 7.4 0 0 1 1.353-1.431a7.3 7.3 0 0 1 2.875-1.431A.998.998 0 0 1 19 3v4.849q.407 1.295.67 2.627A19 19 0 0 1 20 14a5.8 5.8 0 0 1-.356 2.036a7 7 0 0 1-.82 1.531l-.013.018a8.06 8.06 0 0 1-2.905 2.48c-3.658 1.873-8.29.879-10.717-2.48l-.013-.018a7 7 0 0 1-.82-1.531A5.8 5.8 0 0 1 4 14a19 19 0 0 1 .33-3.524q.263-1.332.67-2.627");
}

</style>
