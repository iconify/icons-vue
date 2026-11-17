<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gu1hcqbvs"/><path class="uejb2_b3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kettle-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gu1hcqbvs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 5v10a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V6.414L4.293 4.707a2 2 0 0 1-.424-.635c-.286-.69-.163-1.561.549-1.932c.18-.093.379-.141.582-.14h9a3 3 0 0 1 3 3");
}

.uejb2_b3q {
  d: path("M21 9v2a3.004 3.004 0 0 1-3 3h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1V9c0-.268-.108-.525-.299-.713A.96.96 0 0 0 18 8h-2a1 1 0 0 1 0-2h2a3 3 0 0 1 3 3M6 20h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>
