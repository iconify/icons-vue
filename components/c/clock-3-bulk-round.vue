<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="oz5busu3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-3-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oz5busu3o {
  d: path("M13 11h4a1 1 0 0 1 0 2h-5a1 1 0 0 1-1-1V7a1 1 0 0 1 2 0Z");
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
