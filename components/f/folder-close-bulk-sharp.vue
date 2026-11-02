<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ub4z9ebsg"/><path class="g6ptozzor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-close-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g6ptozzor {
  d: path("m12 11.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 13l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 14.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 13l-1.293-1.293a.999.999 0 1 1 1.414-1.414Z");
}

.ub4z9ebsg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 3c.265 0 .52.105.707.293L12.414 5H21a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Z");
}

</style>
