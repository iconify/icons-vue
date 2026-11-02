<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wb73dcc1r"/><path class="rifzc1e8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:key-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rifzc1e8o {
  d: path("m11.293 11.293l7-7v-.001l2-1.999a.999.999 0 1 1 1.414 1.414L20.414 5l1.293 1.293a.999.999 0 1 1-1.414 1.414L19 6.414L17.414 8l1.293 1.293a.999.999 0 1 1-1.414 1.414L16 9.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414");
}

.wb73dcc1r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 16a6 6 0 1 1 12 0a6 6 0 0 1-12 0");
}

</style>
