<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v7xcthz1e"/><path class="eligpbc_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-4-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eligpbc_m {
  d: path("M9 7h2a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 1h4a1 1 0 0 1 1 1v10h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h15v-9h-3a1 1 0 0 1 0-2m-6 3h2a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

.v7xcthz1e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 4a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm5 5h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2m0 4h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2");
}

</style>
