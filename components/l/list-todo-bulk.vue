<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t-5fob3rj"/><path class="l2r8ybc_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-todo-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l2r8ybc_c {
  d: path("M21 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 10a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

.t-5fob3rj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2m0 6h4V5H4Zm1 8.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

</style>
