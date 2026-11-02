<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w6h-zwjov"/><path class="hp5p-wbnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-electric-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hp5p-wbnk {
  d: path("M13.707 8.707L12.414 10H14a1.002 1.002 0 0 1 .707 1.707l-3 3a.999.999 0 1 1-1.414-1.414L11.586 12H10a1.002 1.002 0 0 1-.707-1.707l3-3a.999.999 0 1 1 1.414 1.414M3 9h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m17 0h1a1 1 0 0 1 0 2h-1a1 1 0 0 1 0-2");
}

.w6h-zwjov {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 18v-8c0-.155.036-.308.106-.447l3-6A1 1 0 0 1 7 3h10c.379 0 .725.214.894.553l3 6c.07.139.106.292.106.447v8a1 1 0 0 1-1 1h-1v1a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1H9v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1H4a1 1 0 0 1-1-1");
}

</style>
