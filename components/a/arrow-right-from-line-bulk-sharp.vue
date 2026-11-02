<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x71w8dboq"/><path class="vu-a9egmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-right-from-line-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vu-a9egmu {
  d: path("M17.586 13H8a1 1 0 0 1 0-2h9.586l-2.293-2.293a.999.999 0 1 1 1.414-1.414l4 4a1 1 0 0 1 0 1.414l-4 4a.999.999 0 1 1-1.414-1.414Z");
}

.x71w8dboq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0");
}

</style>
