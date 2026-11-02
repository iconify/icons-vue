<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ldmad_xfq"/><path class="pu2sv5btb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-left-from-line-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ldmad_xfq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0");
}

.pu2sv5btb {
  d: path("M6.414 11H16a1 1 0 0 1 0 2H6.414l2.293 2.293a.999.999 0 1 1-1.414 1.414l-4-4a1 1 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414Z");
}

</style>
