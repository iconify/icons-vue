<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pfpqefblu"/><path class="x9g_vubfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pfpqefblu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 4a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

.x9g_vubfm {
  d: path("M8 19v-5c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l5 5A1 1 0 0 1 20 14v5h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm2 0h8v-4.586l-4-4l-4 4Z");
}

</style>
