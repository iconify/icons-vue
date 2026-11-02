<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="suz3f6b8m"/><path class="khay96b3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-to-line-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.khay96b3w {
  d: path("M13 10.414V20a1 1 0 0 1-2 0v-9.586l-2.293 2.293a.999.999 0 1 1-1.414-1.414l4-4a.997.997 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414Z");
}

.suz3f6b8m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>
