<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bz2wx0ban"/><path class="oidse6wjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-help-bulk-round" /></template>
<style>
.bz2wx0ban {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m17.707 18.707l-2 2a5.243 5.243 0 0 1-7.414 0l-5-5a5.243 5.243 0 0 1 0-7.414l5-5a5.243 5.243 0 0 1 7.414 0l5 5a5.243 5.243 0 0 1 0 7.414Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.oidse6wjy {
  d: path("M9 11a3 3 0 1 1 3 3a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 11 11a1 1 0 0 1-2 0m3 4h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
