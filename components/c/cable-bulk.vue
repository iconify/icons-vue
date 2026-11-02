<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="paq28ebve"/><path class="w6lj68kwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.paq28ebve {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 4h4a3 3 0 1 1 0 6H5a3 3 0 1 1 0-6m10 10h4a3 3 0 1 1 0 6h-4a3 3 0 1 1 0-6");
}

.w6lj68kwe {
  d: path("M6 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM6 9a1 1 0 0 1 2 0v1.001A1 1 0 0 0 9 11h6a3 3 0 0 1 3 3v1a1 1 0 0 1-2 0v-1.001A1 1 0 0 0 15 13H8.999c-.796 0-1.56-.317-2.122-.881A3 3 0 0 1 6 10Zm8 12v-2a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0m6 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
