<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u8sw8ofgw"/><path class="j7dazybkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-edit-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j7dazybkc {
  d: path("M9 8a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1Zm-1 8c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 11 19H9a1 1 0 0 1-1-1Z");
}

.u8sw8ofgw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 5a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

</style>
