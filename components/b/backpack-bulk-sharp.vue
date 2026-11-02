<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i1gueypsl"/><path class="gu0cbsbnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backpack-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gu0cbsbnu {
  d: path("M9 3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V4h-2v3a1 1 0 0 1-2 0Zm7 7a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2ZM7 21v-5a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v5a1 1 0 0 1-2 0v-4H9v4a1 1 0 0 1-2 0");
}

.i1gueypsl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 6h16a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1");
}

</style>
