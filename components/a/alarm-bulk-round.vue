<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rxtmbxbvl"/><path class="a09ee3jto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:alarm-bulk-round" /></template>
<style>
.a09ee3jto {
  d: path("M5.293 2.293a.999.999 0 1 1 1.414 1.414l-3 3a.999.999 0 1 1-1.414-1.414Zm13.414 0l3 3a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 1.414-1.414M13 12h3a1 1 0 0 1 0 2h-4a1 1 0 0 1-1-1V9a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.rxtmbxbvl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 13a9 9 0 0 1 9-9a9 9 0 0 1 9 9a9 9 0 0 1-9 9a9 9 0 0 1-9-9");
}

</style>
