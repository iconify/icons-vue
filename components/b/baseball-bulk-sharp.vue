<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="yw2-qdbnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:baseball-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

.yw2-qdbnv {
  d: path("M12.214 6.893a9.9 9.9 0 0 1-2.143 3.178a9.9 9.9 0 0 1-3.178 2.143A9.9 9.9 0 0 1 3 13a1 1 0 0 1 0-2a7.9 7.9 0 0 0 3.114-.628a7.9 7.9 0 0 0 2.543-1.715a7.9 7.9 0 0 0 1.715-2.543A7.9 7.9 0 0 0 11 3a1 1 0 0 1 2 0a9.9 9.9 0 0 1-.786 3.893m-.428 10.214a9.9 9.9 0 0 1 2.143-3.178a9.9 9.9 0 0 1 3.178-2.143A9.9 9.9 0 0 1 21 11a1 1 0 0 1 0 2a7.9 7.9 0 0 0-3.114.628a7.9 7.9 0 0 0-2.543 1.715a7.9 7.9 0 0 0-1.715 2.543A7.9 7.9 0 0 0 13 21a1 1 0 0 1-2 0a9.9 9.9 0 0 1 .786-3.893");
}

</style>
