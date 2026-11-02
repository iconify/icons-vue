<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zkf_sabyk"/><path class="me-xsyi0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.me-xsyi0z {
  d: path("m9.707 9.293l6 6a.999.999 0 1 1-1.414 1.414l-6-6a.999.999 0 1 1 1.414-1.414M11 19h10a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2");
}

.zkf_sabyk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m6.293 20.707l-4-4a1 1 0 0 1 0-1.414l12-12a1 1 0 0 1 1.414 0l6 6a1 1 0 0 1 0 1.414l-10 10A1 1 0 0 1 11 21H7a1 1 0 0 1-.707-.293");
}

</style>
