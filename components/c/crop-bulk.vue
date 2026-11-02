<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y32rrcc0n"/><path class="d23djdbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crop-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d23djdbts {
  d: path("M7 6v10a1 1 0 0 0 1 1h13a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H8a3 3 0 0 1-3-3V7H3a1 1 0 0 1 0-2h2V3a1 1 0 0 1 2 0Z");
}

.y32rrcc0n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 5a3 3 0 0 1 3 3v6a1 1 0 0 1-2 0V8a1 1 0 0 0-1-1h-6a1 1 0 0 1 0-2Z");
}

</style>
