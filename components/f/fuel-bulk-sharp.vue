<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d0vykxf0y"/><path class="z8h8-vbxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fuel-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d0vykxf0y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.z8h8-vbxe {
  d: path("M13 11h4a1 1 0 0 1 1 1v4h2V7.414l-2.707-2.707a.999.999 0 1 1 1.414-1.414l3 3A1 1 0 0 1 22 7v10a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-4h-3a1 1 0 0 1 0-2M3 8h10a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
