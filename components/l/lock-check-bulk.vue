<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u294wob9d"/><path class="ic_c64bzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-check-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ic_c64bzx {
  d: path("M8 10V6a4 4 0 0 1 8 0v4a1 1 0 0 1-2 0V6a2 2 0 1 0-4 0v4a1 1 0 0 1-2 0m.707 4.293L11 16.586l4.293-4.293a.999.999 0 1 1 1.414 1.414l-5 5a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414");
}

.u294wob9d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 12a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

</style>
