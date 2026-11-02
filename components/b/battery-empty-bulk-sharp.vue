<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dyo4c8bkh"/><path class="e4boz2bdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-empty-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dyo4c8bkh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a1 1 0 0 1 1-1h15a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.e4boz2bdl {
  d: path("M22 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
