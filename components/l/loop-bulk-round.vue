<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fw86-bbfx"/><path class="dl6v1-bdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:loop-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dl6v1-bdz {
  d: path("M15 17h2a3 3 0 0 0 3-3v-4a3 3 0 0 0-3-3H7a3 3 0 0 0-3 3v4a3 3 0 0 0 3 3h1.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L8.586 19H7a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 19h-2a1 1 0 0 1 0-2");
}

.fw86-bbfx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 10a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

</style>
