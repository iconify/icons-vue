<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f1_kkbbdy"/><path class="qh8t6jbdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:column-plus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f1_kkbbdy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7a4 4 0 0 1 8 0v10a4 4 0 0 1-8 0Z");
}

.qh8t6jbdp {
  d: path("M18 9v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2V9a1 1 0 0 1 2 0");
}

</style>
