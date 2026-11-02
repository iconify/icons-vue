<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n--sluzms"/><path class="l2r8ybc_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-todo-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l2r8ybc_c {
  d: path("M21 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 10a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

.n--sluzms {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1ZM4 5v4h4V5Zm1 12.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

</style>
