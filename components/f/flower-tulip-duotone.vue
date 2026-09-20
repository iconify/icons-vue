<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="igifs5bqg"/><path class="n6tmk_bap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:flower-tulip-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.igifs5bqg {
  d: path("M169.23 66A80 80 0 0 0 128 136a80 80 0 0 0-41.23-70C100 38 128 24 128 24s28 14 41.23 42");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n6tmk_bap {
  d: path("M208 48a87.5 87.5 0 0 0-35.36 7.43c-15.1-25.37-39.92-38-41.06-38.59a8 8 0 0 0-7.16 0c-1.14.58-26 13.22-41.06 38.59A87.5 87.5 0 0 0 48 48a8 8 0 0 0-8 8v40a88.11 88.11 0 0 0 80 87.63v35.43l-36.42-18.22a8 8 0 1 0-7.16 14.32l48 24a8 8 0 0 0 7.16 0l48-24a8 8 0 0 0-7.16-14.32L136 219.06v-35.43A88.11 88.11 0 0 0 216 96V56a8 8 0 0 0-8-8m-80-14.79c6.65 4.08 21.08 14.19 30.64 30A88.46 88.46 0 0 0 128 99.36a88.4 88.4 0 0 0-30.64-36.17c9.57-15.79 23.99-25.9 30.64-29.98M56 96V64.44A72.1 72.1 0 0 1 120 136v31.56A72.1 72.1 0 0 1 56 96m144 0a72.1 72.1 0 0 1-64 71.56V136a72.1 72.1 0 0 1 64-71.56Z");
}

</style>
