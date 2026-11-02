<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="euw4ylplj"/><path class="u-2brwj7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-minus-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.euw4ylplj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 14h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

.u-2brwj7e {
  d: path("M14 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm-4 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
