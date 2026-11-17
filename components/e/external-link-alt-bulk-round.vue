<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="enc56dnmh"/><path class="k_i_my6jr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:external-link-alt-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.enc56dnmh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 19V9a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4Z");
}

.k_i_my6jr {
  d: path("M14 18h1a3 3 0 0 0 3-3V9a3 3 0 0 0-3-3H9a3 3 0 0 0-3 3v1a1 1 0 0 1-2 0V9a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 20h-1a1 1 0 0 1 0-2m-4 2a1 1 0 0 1-2 0v-2.586l-4.293 4.293a.999.999 0 1 1-1.414-1.414L6.586 16H4a1 1 0 0 1 0-2h5a1 1 0 0 1 1 1Z");
}

</style>
