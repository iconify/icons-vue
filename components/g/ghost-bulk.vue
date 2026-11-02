<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f154krbzo"/><path class="m_qqm-b_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ghost-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f154krbzo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11a9 9 0 0 1 9-9a9 9 0 0 1 9 9v8c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-1-1a1.83 1.83 0 0 0-2.586 0a3.8 3.8 0 0 1-1.267.841a3.8 3.8 0 0 1-1.44.28a3.8 3.8 0 0 1-1.44-.28a3.8 3.8 0 0 1-1.267-.841a1.83 1.83 0 0 0-2.586 0l-1 1a1.36 1.36 0 0 1-1.186.382C3.572 20.928 3 19.898 3 19Z");
}

.m_qqm-b_v {
  d: path("M9 9h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2");
}

</style>
