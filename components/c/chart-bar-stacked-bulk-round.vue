<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nybpznbdz"/><path class="jqyqz0bst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-stacked-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jqyqz0bst {
  d: path("M14 14v-1h-4v7a1 1 0 0 1-2 0v-4H3a1 1 0 0 1 0-2h5v-3a1 1 0 0 1 2 0h4V8a1 1 0 0 1 2 0v5h5a1 1 0 0 1 0 2h-5v5a1 1 0 0 1-2 0Z");
}

.nybpznbdz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 6a3 3 0 1 1 6 0v14a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1Zm13 4v10a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V10a3 3 0 0 1 6 0M2 13a2.999 2.999 0 1 1 6 0v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
