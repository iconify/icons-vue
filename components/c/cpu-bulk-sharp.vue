<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a7tg6wros"/><path class="pzkmfcqvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-bulk-sharp" /></template>
<style>
.a7tg6wros {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.pzkmfcqvq {
  d: path("M11 6a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM6 9a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm3 1a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1Zm9-1h3a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2m-7 4h2v-2h-2Zm-5 0a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm12 0h3a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2m-7 5v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0m4 0v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0");
}

</style>
