<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="dy9gnccmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-pause-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dy9gnccmp {
  d: path("M11 9v6a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0m4 0v6a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0");
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
