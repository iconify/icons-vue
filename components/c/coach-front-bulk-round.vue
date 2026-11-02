<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="otql1vahh"/><path class="cj0yk--lw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coach-front-bulk-round" /></template>
<style>
.cj0yk--lw {
  d: path("M8.01 14a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm8 0a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.otql1vahh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 2h8a5 5 0 0 1 5 5v9c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1H9v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 3 16V7a5 5 0 0 1 5-5m0 2a3 3 0 0 0-3 3v4h14V7a3 3 0 0 0-3-3Z");
}

</style>
