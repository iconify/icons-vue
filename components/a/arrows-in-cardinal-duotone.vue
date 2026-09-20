<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="kbgxg_7rn"/><path class="kagqseb0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-in-cardinal-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kagqseb0j {
  d: path("M90.34 69.66a8 8 0 0 1 11.32-11.32L120 76.69V24a8 8 0 0 1 16 0v52.69l18.34-18.35a8 8 0 0 1 11.32 11.32l-32 32a8 8 0 0 1-11.32 0Zm43.32 84.68a8 8 0 0 0-11.32 0l-32 32a8 8 0 0 0 11.32 11.32L120 179.31V232a8 8 0 0 0 16 0v-52.69l18.34 18.35a8 8 0 0 0 11.32-11.32ZM232 120h-52.69l18.35-18.34a8 8 0 0 0-11.32-11.32l-32 32a8 8 0 0 0 0 11.32l32 32a8 8 0 0 0 11.32-11.32L179.31 136H232a8 8 0 0 0 0-16m-130.34 2.34l-32-32a8 8 0 0 0-11.32 11.32L76.69 120H24a8 8 0 0 0 0 16h52.69l-18.35 18.34a8 8 0 0 0 11.32 11.32l32-32a8 8 0 0 0 0-11.32");
}

.kbgxg_7rn {
  d: path("M224 48v160a16 16 0 0 1-16 16H48a16 16 0 0 1-16-16V48a16 16 0 0 1 16-16h160a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
