<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ygqlu6xwg"/><path class="wz_3ew2hq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fridge-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wz_3ew2hq {
  d: path("M16 6v1a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0M5 9h14a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2m11 5v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0");
}

.ygqlu6xwg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3Z");
}

</style>
