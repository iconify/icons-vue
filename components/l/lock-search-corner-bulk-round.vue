<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p1wljk6dr"/><path class="g84vqppsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-search-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g84vqppsq {
  d: path("M17 7v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0m4.321 12.907l1.386 1.386a.999.999 0 1 1-1.414 1.414l-1.386-1.386a3.83 3.83 0 1 1 1.414-1.414m-2.028-.614a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586");
}

.p1wljk6dr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 22H8a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5h8a4.9 4.9 0 0 1 2.5.67a4.9 4.9 0 0 1 1.83 1.83a.997.997 0 0 1-.366 1.366a1 1 0 0 1-.5.134H15c-.796 0-1.559.316-2.121.879A3 3 0 0 0 12 15v6a1 1 0 0 1-1 1");
}

</style>
