<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rz6lzbchz"/><path class="yka26actg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-warning-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rz6lzbchz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 22H6a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3a1 1 0 0 1-1 1h-7a.997.997 0 0 0-1 1v8a1 1 0 0 1-1 1");
}

.yka26actg {
  d: path("M17 7v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0m2 8v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0m-1 5h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

</style>
