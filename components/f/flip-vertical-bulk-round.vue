<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o4e3o36cz"/><path class="jvfhggt3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jvfhggt3x {
  d: path("M7 11a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Z");
}

.o4e3o36cz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 2h6c.898 0 1.928.572 2.089 1.521a1.34 1.34 0 0 1-.382 1.186l-3 3a2.414 2.414 0 0 1-3.414 0l-3-3a1.36 1.36 0 0 1-.382-1.186C7.072 2.572 8.102 2 9 2m6 20H9c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l3-3a2.414 2.414 0 0 1 3.414 0l3 3c.311.31.456.752.382 1.186C16.928 21.428 15.898 22 15 22");
}

</style>
