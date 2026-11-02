<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qnuo2e4sb"/><path class="uu8iy5mdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-horizontal-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qnuo2e4sb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 15V9c0-.898.572-1.928 1.521-2.089a1.34 1.34 0 0 1 1.186.382l3 3a2.414 2.414 0 0 1 0 3.414l-3 3a1.36 1.36 0 0 1-1.186.382C2.572 16.928 2 15.898 2 15m20-6v6c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-3-3a2.414 2.414 0 0 1 0-3.414l3-3a1.36 1.36 0 0 1 1.186-.382C21.428 7.072 22 8.102 22 9");
}

.uu8iy5mdc {
  d: path("M13 7a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm0 6a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm0 6a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
