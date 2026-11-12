<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p6hxz1btw"/><path class="vuavclhzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:decimal-decrease-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p6hxz1btw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 5v2a3 3 0 1 1-6 0V5a3 3 0 1 1 6 0m-4 0v2a1 1 0 0 0 2 0V5a1 1 0 0 0-2 0");
}

.vuavclhzl {
  d: path("M10 5a3 3 0 1 1 6 0v2a3 3 0 1 1-6 0Zm2 0v2a1 1 0 0 0 2 0V5a1 1 0 0 0-2 0M7.01 8a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm-.303 7.707L5.414 17H21a1 1 0 0 1 0 2H5.414l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414");
}

</style>
