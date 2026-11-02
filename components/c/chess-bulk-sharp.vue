<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="luii9mbbn"/><path class="dz2wkxbbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chess-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dz2wkxbbs {
  d: path("M5 17a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Zm2 3h10v-2H7Z");
}

.luii9mbbn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h1.279l1.334-4H7a1 1 0 0 1-.894-.553l-1-2A1 1 0 0 1 5.4 8.2l3.423-2.568l-.772-2.316a1.001 1.001 0 0 1 1.265-1.265l3 1c1.666.556 2.921 1.688 3.703 3.252C16.744 7.753 17 9.391 17 11v5Z");
}

</style>
