<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v67uszbsv"/><path class="wc_-ddckz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bandwidth-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.v67uszbsv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.414 11h7.172l-1.293-1.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L15.586 13H8.414l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414Z");
}

.wc_-ddckz {
  d: path("M21 4a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm0 14a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
