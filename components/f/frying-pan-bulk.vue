<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sodqk3r6m"/><path class="hy-_s9som"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:frying-pan-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hy-_s9som {
  d: path("m14.553 10.106l6-3a1 1 0 1 1 .894 1.788l-6 3a1 1 0 1 1-.894-1.788");
}

.sodqk3r6m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 10a1 1 0 0 1 1 1v3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-3a1 1 0 0 1 1-1Z");
}

</style>
