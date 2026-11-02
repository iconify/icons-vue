<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bqfhchcjm"/><path class="obs5sfbko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-bulk" /></template>
<style>
.bqfhchcjm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 6a3 3 0 0 1 3 3v8c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128h-.342a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 4 17V9a3 3 0 0 1 3-3ZM9.705 19.709l.002-.002l.002-.002a1 1 0 0 0-.002-1.412l-.002-.002a1 1 0 1 0 0 1.418m4.588-.002l.002.002a1 1 0 1 0 0-1.418l-.002.002l-.002.002a1 1 0 0 0 .002 1.412");
}

.cuyn6tgcc {
  fill: currentColor;
}

.obs5sfbko {
  d: path("M10 2h4.001A2 2 0 0 1 16 4v3a1 1 0 0 1-2 0V4h-4v3a1 1 0 0 1-2 0V4a2 2 0 0 1 2-2M6 19a3 3 0 1 1 6 0a3 3 0 0 1-6 0m6.236 1.168a3 3 0 1 1 5.527-2.335a3 3 0 0 1-5.527 2.335M8 19a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
