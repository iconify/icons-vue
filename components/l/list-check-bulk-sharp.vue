<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ygnr8tboz"/><path class="u-2brwj7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-check-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u-2brwj7e {
  d: path("M14 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm-4 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

.ygnr8tboz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m17 15.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

</style>
