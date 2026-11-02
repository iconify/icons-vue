<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="w7uwd1ncb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-play-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

.w7uwd1ncb {
  d: path("m12.555 8.168l3 2a2.202 2.202 0 0 1 0 3.664l-3 2c-1.054.702-2.501.442-3.2-.628A2.2 2.2 0 0 1 9 14v-4c0-.428.121-.845.355-1.204c.699-1.07 2.146-1.33 3.2-.628M11 14c0 .087.05.155.127.193c.106.053.22.04.318-.025l3-2a.203.203 0 0 0 0-.336l-3-2a.31.31 0 0 0-.318-.025A.21.21 0 0 0 11 10Z");
}

</style>
