<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="panz28b2u"/><path class="cevczpb5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-rebase-bulk" /></template>
<style>
.cevczpb5c {
  d: path("M7 5h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2M4 16V8a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0m9.414-4H17a3.004 3.004 0 0 1 3 3v6a1 1 0 0 1-2 0v-6a1 1 0 0 0-1-1h-3.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.panz28b2u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m14 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0M2 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
