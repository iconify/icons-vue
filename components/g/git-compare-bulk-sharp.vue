<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wd4ygnuuu"/><path class="wd9uczbmb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-compare-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wd4ygnuuu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m14 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

.wd9uczbmb {
  d: path("M13.414 5H19a1 1 0 0 1 1 1v10a1 1 0 0 1-2 0V7h-4.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414ZM4 18V8a1 1 0 0 1 2 0v9h4.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L10.586 19H5a1 1 0 0 1-1-1");
}

</style>
