<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qsoi9xbml"/><path class="j_t9mdb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barn-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j_t9mdb9v {
  d: path("M9 10a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0M3 22a1 1 0 0 1 0-2h5v-2a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v2h5a1 1 0 0 1 0 2Zm11-2v-2a1 1 0 0 0-1-1h-2a1 1 0 0 0-1 1v2Z");
}

.qsoi9xbml {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 21v-9.667c0-1.082.351-2.134 1-3l1.73-2.306a5 5 0 0 1 1.427-1.288l2.271-1.362a5 5 0 0 1 5.144 0l2.271 1.362c.555.332 1.04.77 1.427 1.288L20 8.333c.649.866 1 1.918 1 3V21a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m7-11a2 2 0 1 0 3.999.001A2 2 0 0 0 10 10m5 8a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2v3h6Z");
}

</style>
