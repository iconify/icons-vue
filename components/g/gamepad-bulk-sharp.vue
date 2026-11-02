<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bc11tac6h"/><path class="wt8ab7bdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gamepad-bulk-sharp" /></template>
<style>
.bc11tac6h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.wt8ab7bdc {
  d: path("M11 9v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H7a1 1 0 0 1 0-2h2V9a1 1 0 0 1 2 0m7 0h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2m-1.99 4a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2Z");
}

</style>
