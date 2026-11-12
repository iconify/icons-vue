<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bnoufibzl"/><path class="wv7q85bsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:logs-bulk" /></template>
<style>
.bnoufibzl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.472 14.664a6.001 6.001 0 1 1 11.055 4.674a6.001 6.001 0 0 1-11.055-4.674m1.842 3.893a4.001 4.001 0 1 0 7.37-3.116a4.001 4.001 0 0 0-7.37 3.116M18 16h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.wv7q85bsy {
  d: path("M21 3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2ZM8 13a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
