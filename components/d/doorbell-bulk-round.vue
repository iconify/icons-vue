<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oiw7w_1ii"/><path class="l0venub_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:doorbell-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l0venub_k {
  d: path("M10 7h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m-1 7a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.oiw7w_1ii {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 7a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 14 22h-4a5 5 0 0 1-5-5Z");
}

</style>
