<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tkc3hmb8q"/><path class="qofaqjbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bridge-suspension-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qofaqjbql {
  d: path("M7 14h10V3a1 1 0 0 1 2 0v11h2a1 1 0 0 1 0 2h-2v3a1 1 0 0 1-2 0v-3H7v3a1 1 0 0 1-2 0v-3H3a1 1 0 0 1 0-2h2V3a1 1 0 0 1 2 0Z");
}

.tkc3hmb8q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m18.707 5.293l3 3a.999.999 0 1 1-1.414 1.414L18.31 7.724A7.32 7.32 0 0 1 13 11.257V15a1 1 0 0 1-2 0v-3.743a7.32 7.32 0 0 1-5.31-3.533L3.707 9.707a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.656.391a5.324 5.324 0 0 0 10.101.003a1.002 1.002 0 0 1 1.657-.394");
}

</style>
