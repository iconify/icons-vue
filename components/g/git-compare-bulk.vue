<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wd4ygnuuu"/><path class="i354j0bzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-compare-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i354j0bzc {
  d: path("M13.414 5H17a3.004 3.004 0 0 1 3 3v8a1 1 0 0 1-2 0V8a1 1 0 0 0-1-1h-3.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414ZM7 17h3.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L10.586 19H7a3 3 0 0 1-3-3V8a1 1 0 0 1 2 0v8a1 1 0 0 0 1 1");
}

.wd4ygnuuu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m14 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
