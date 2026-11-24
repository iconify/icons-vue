<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rz6lzbchz"/><path class="v0myoabtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-plus-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rz6lzbchz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 22H6a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3a1 1 0 0 1-1 1h-7a.997.997 0 0 0-1 1v8a1 1 0 0 1-1 1");
}

.v0myoabtg {
  d: path("M17 7v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0m2 8v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0");
}

</style>
