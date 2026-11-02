<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="suz3f6b8m"/><path class="j6ohxacnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-from-line-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j6ohxacnz {
  d: path("m11.293 20.707l-4-4a.999.999 0 1 1 1.414-1.414L11 17.586V8a1 1 0 0 1 2 0v9.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0");
}

.suz3f6b8m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>
