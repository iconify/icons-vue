<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gm4t3m1vu"/><path class="tbyfcnbgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gm4t3m1vu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 8a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3Z");
}

.tbyfcnbgu {
  d: path("M11 6a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM6 9a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm5 0h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2m7 0h3a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2m-7 4h2v-2h-2Zm-5 0a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm12 0h3a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2m-7 5v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0m4 0v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0");
}

</style>
