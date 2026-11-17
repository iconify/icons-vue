<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qxd7zebey"/><path class="uuea8obgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cooking-pot-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qxd7zebey {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 10a1 1 0 0 1 1 1v7a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-7a1 1 0 0 1 1-1h.366a7.5 7.5 0 0 1 13.268 0Z");
}

.uuea8obgy {
  d: path("M14 5h-1v2a1 1 0 0 1-2 0V5h-1a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2m5 7H5a1 1 0 0 1 0-2h14a1 1 0 0 1 0 2M5 15H3a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2m16 0h-2a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2");
}

</style>
