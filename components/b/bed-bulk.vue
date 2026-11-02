<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ldtdlfb8l"/><path class="jxdgqbbmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bed-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jxdgqbbmf {
  d: path("M4 8h15a3 3 0 0 1 3 3v8a1 1 0 0 1-2 0v-8a1 1 0 0 0-1-1H8v6a1 1 0 0 1-2 0v-6H4v9a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

.ldtdlfb8l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8h16a3 3 0 0 1 3 3v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1");
}

</style>
