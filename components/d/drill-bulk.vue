<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nzsebfl-m"/><path class="nfqcfp0_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drill-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nfqcfp0_n {
  d: path("M18 8a1 1 0 0 1 0-2h3a1 1 0 0 1 0 2Z");
}

.nzsebfl-m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 0 1 3-3h8c.856 0 1.667.36 2.236 1H17a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-1.764A3 3 0 0 1 13 11h-1v4.171A3.001 3.001 0 0 1 11 21H7a3 3 0 0 1-1-5.829V11H5a3 3 0 0 1-3-3Z");
}

</style>
