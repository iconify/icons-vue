<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ggx0oswmo"/><path class="q4hvc5b_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:loop-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ggx0oswmo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6h18v12H3Z");
}

.q4hvc5b_o {
  d: path("M15 17h5V7H4v10h4.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L8.586 19H3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-6a1 1 0 0 1 0-2");
}

</style>
