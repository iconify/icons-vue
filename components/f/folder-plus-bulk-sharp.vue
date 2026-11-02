<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ub4z9ebsg"/><path class="zxhfeujqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-plus-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ub4z9ebsg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 3c.265 0 .52.105.707.293L12.414 5H21a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Z");
}

.zxhfeujqd {
  d: path("M13 12h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0Z");
}

</style>
