<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y91ep0b0f"/><path class="ipe5k6bwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fold-vertical-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ipe5k6bwf {
  d: path("m11.292 10.707l-2.999-3a.999.999 0 1 1 1.414-1.414L11 7.586V3a1 1 0 0 1 2 0v4.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0ZM13 16.414V21a1 1 0 0 1-2 0v-4.586l-1.293 1.293a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414Z");
}

.y91ep0b0f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 11a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm12 0a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
