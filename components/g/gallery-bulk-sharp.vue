<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a39lbxsnp"/><path class="ihx62db9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gallery-bulk-sharp" /></template>
<style>
.a39lbxsnp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ihx62db9q {
  d: path("M8.293 6.293a.997.997 0 0 1 1.414 0L14 10.586l2.293-2.293a1 1 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414L17 10.414l-2.293 2.293a1 1 0 0 1-1.414 0L9 8.414l-5.293 5.293a.999.999 0 1 1-1.414-1.414ZM10 20a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm11 0a1 1 0 0 1 0 2h-7a1 1 0 0 1 0-2Z");
}

</style>
