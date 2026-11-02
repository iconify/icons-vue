<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qh5667bww"/><path class="ox78qebke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bike-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ox78qebke {
  d: path("m9.781 6l-.5 2h5.438l-.689-2.757A.998.998 0 0 1 15 4h3a3 3 0 0 1 3 3a1 1 0 0 1-2 0a1 1 0 0 0-1-1h-1.719l.689 2.757v.001l.812 3.247A5 5 0 1 1 13 17.002V17a4.99 4.99 0 0 1 2.841-4.511L15.219 10H8.781l-.622 2.489A5.001 5.001 0 1 1 1 17v-.001c0-1.365.558-2.67 1.545-3.613a4.98 4.98 0 0 1 3.673-1.381L7.719 6H6a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2Zm8.503 8.013l.686 2.744a1 1 0 0 1-1.94.486l-.686-2.745a3 3 0 1 0 1.94-.485m-10.628.485l-.686 2.745a1 1 0 0 1-1.94-.486l.686-2.744a3 3 0 1 0 1.94.485");
}

.qh5667bww {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1.393 15.053a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896m12 0a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896M5 17a1 1 0 1 0 2 0a1 1 0 0 0-2 0m12 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
