<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n05v-kbpq"/><path class="ennarlb-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:certificate-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ennarlb-g {
  d: path("M17 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm1 9.38V21a1.002 1.002 0 0 1-1.707.707L15 20.414l-1.293 1.293A1 1 0 0 1 12 21v-5.62a3.828 3.828 0 0 1 5.601-5.189A3.83 3.83 0 0 1 18 15.38M9 10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm4.707 4.293a1.829 1.829 0 1 0 2.586-2.587a1.829 1.829 0 0 0-2.586 2.587M14 16.697v1.889l.293-.293a1 1 0 0 1 1.414 0l.293.293v-1.889a3.9 3.9 0 0 1-2 0");
}

.n05v-kbpq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3h-1v3a1.002 1.002 0 0 1-1.707.707L15 20.414l-1.293 1.293A1 1 0 0 1 12 21v-3H5a3 3 0 0 1-3-3Z");
}

</style>
