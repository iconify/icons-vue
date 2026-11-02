<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p7qta0bol"/><path class="em_6rpxdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.em_6rpxdx {
  d: path("M9.414 10h5.172l5.707-5.707a.999.999 0 1 1 1.414 1.414l-6 6A1 1 0 0 1 15 12H9a1 1 0 0 1-.707-.293l-6-6a.999.999 0 1 1 1.414-1.414Z");
}

.p7qta0bol {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 20H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1");
}

</style>
