<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k4wyalqta"/><path class="fopn574jx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-edit-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fopn574jx {
  d: path("M17 7v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0m-4 11c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 17 22h-3a1 1 0 0 1-1-1Z");
}

.k4wyalqta {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 22H4a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-9v9a1 1 0 0 1-1 1");
}

</style>
