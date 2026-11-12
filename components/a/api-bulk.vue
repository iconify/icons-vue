<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e1__egbfy"/><path class="mge6njria"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:api-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e1__egbfy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 11h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

.mge6njria {
  d: path("m4.414 12l3.293 3.293a.999.999 0 1 1-1.414 1.414l-4-4a1 1 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414Zm17.293-.707a1 1 0 0 1 0 1.414l-4 4a.999.999 0 1 1-1.414-1.414L19.586 12l-3.293-3.293a.999.999 0 1 1 1.414-1.414Z");
}

</style>
