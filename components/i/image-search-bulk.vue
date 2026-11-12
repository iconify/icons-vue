<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ye6cy2b2f"/><path class="g47fxpqso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-search-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g47fxpqso {
  d: path("m16.708 9.293l1.999 2a.999.999 0 1 1-1.414 1.414l-2-1.999a3 3 0 1 1 1.415-1.415M13 8a1 1 0 1 0 2 0a1 1 0 0 0-2 0M2.293 16.293l3-3a2.415 2.415 0 0 1 3.414 0l7 7a.999.999 0 1 1-1.414 1.414l-7-7a.415.415 0 0 0-.586 0l-3 3a.999.999 0 1 1-1.414-1.414");
}

.ye6cy2b2f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 2a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3Z");
}

</style>
