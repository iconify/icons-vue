<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jahhv7bmc"/><path class="g9tivhbor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:images-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g9tivhbor {
  d: path("M7 2h10a5 5 0 0 1 5 5v10a1 1 0 0 1-2 0V7a3 3 0 0 0-3-3H7a1 1 0 0 1 0-2M2.293 16.293l3-3a3.83 3.83 0 0 1 5.414 0l1 1a.414.414 0 0 0 .586 0a2.41 2.41 0 0 1 3.414 0l2 2a.999.999 0 1 1-1.414 1.414l-2-2a.414.414 0 0 0-.586 0a2.41 2.41 0 0 1-3.414 0l-1-1a1.83 1.83 0 0 0-2.586 0l-3 3a.999.999 0 1 1-1.414-1.414");
}

.jahhv7bmc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Z");
}

</style>
