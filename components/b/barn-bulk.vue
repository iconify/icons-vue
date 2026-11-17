<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v1l1apb9j"/><path class="j_t9mdb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barn-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j_t9mdb9v {
  d: path("M9 10a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0M3 22a1 1 0 0 1 0-2h5v-2a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v2h5a1 1 0 0 1 0 2Zm11-2v-2a1 1 0 0 0-1-1h-2a1 1 0 0 0-1 1v2Z");
}

.v1l1apb9j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 21V10.667c0-.649.211-1.281.6-1.8l2.365-3.154c.232-.311.523-.573.856-.772l3.636-2.181c.95-.57 2.136-.57 3.086 0l3.636 2.181c.333.199.624.461.856.772L20.4 8.867c.389.519.6 1.151.6 1.8V21a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m7-11a2 2 0 1 0 3.999.001A2 2 0 0 0 10 10m5 8a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2v3h6Z");
}

</style>
