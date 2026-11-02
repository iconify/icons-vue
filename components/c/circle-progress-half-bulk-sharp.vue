<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="d09z33sio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-progress-half-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d09z33sio {
  d: path("M11 7a1 1 0 0 1 1-1a5.9 5.9 0 0 1 2.336.472c.713.3 1.361.737 1.907 1.285A5.98 5.98 0 0 1 18 12a5.97 5.97 0 0 1-1.757 4.243a6 6 0 0 1-1.907 1.285A5.9 5.9 0 0 1 12 18a1 1 0 0 1-1-1Zm2 8.875a4.002 4.002 0 0 0 0-7.75Z");
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
