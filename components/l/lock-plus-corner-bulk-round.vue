<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p1wljk6dr"/><path class="v0myoabtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-plus-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p1wljk6dr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 22H8a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5h8a4.9 4.9 0 0 1 2.5.67a4.9 4.9 0 0 1 1.83 1.83a.997.997 0 0 1-.366 1.366a1 1 0 0 1-.5.134H15c-.796 0-1.559.316-2.121.879A3 3 0 0 0 12 15v6a1 1 0 0 1-1 1");
}

.v0myoabtg {
  d: path("M17 7v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0m2 8v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0");
}

</style>
