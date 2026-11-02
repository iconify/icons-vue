<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ub4xlibmk"/><path class="c5_jg6bea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:figma-bulk-sharp" /></template>
<style>
.c5_jg6bea {
  d: path("M9 2h3a1 1 0 0 1 1 1v5.535a4 4 0 1 1 0 6.93V18a4 4 0 1 1-4-4h2.535a4.01 4.01 0 0 1 0-4H9a3.998 3.998 0 0 1-3.464-6A4 4 0 0 1 9 2m0 2a2 2 0 1 0 0 4h2V4Zm4 8a2 2 0 1 0 3.999.001A2 2 0 0 0 13 12m-4 4a2 2 0 1 0 2 2v-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ub4xlibmk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 2a4 4 0 0 1 2.646 7A4 4 0 0 1 13 15.465V18a4 4 0 1 1-6.646-3a4 4 0 0 1 0-6A4 4 0 0 1 9 2Z");
}

</style>
