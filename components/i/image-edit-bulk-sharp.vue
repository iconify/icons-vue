<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="td1bzxb2d"/><path class="r0tfd2bjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r0tfd2bjr {
  d: path("M11 9c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 14 12h-2a1 1 0 0 1-1-1Zm-4.707 3.293a1 1 0 0 1 1.414 0l8 8a.999.999 0 1 1-1.414 1.414L7 14.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414Z");
}

.td1bzxb2d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

</style>
