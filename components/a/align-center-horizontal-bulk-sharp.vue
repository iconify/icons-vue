<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qicw0us2n"/><path class="eh8x-4blr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-horizontal-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eh8x-4blr {
  d: path("M13 21a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Z");
}

.qicw0us2n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Zm-2 10a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1Z");
}

</style>
