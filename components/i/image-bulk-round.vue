<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wr_1xqtvh"/><path class="dhm3_ccnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dhm3_ccnd {
  d: path("M13.158 7.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-6.865 5.072a3.83 3.83 0 0 1 5.414 0l2 2a.415.415 0 0 0 .586 0l1-1a2.415 2.415 0 0 1 3.414 0l3 3a.999.999 0 1 1-1.414 1.414l-3-3a.415.415 0 0 0-.586 0l-1 1a2.415 2.415 0 0 1-3.414 0l-2-2a1.83 1.83 0 0 0-2.586 0l-4 4a.999.999 0 1 1-1.414-1.414Z");
}

.wr_1xqtvh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 2a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5Z");
}

</style>
