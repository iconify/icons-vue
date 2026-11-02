<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ih_51cbzi"/><path class="oad19bckv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-plus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ih_51cbzi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 3a5 5 0 0 1 5 5v10c0 .285-.076.563-.225.806c-.624 1.009-2.073.939-3.064.629a4.9 4.9 0 0 1-1.266-.603L12 17.202l-2.445 1.63a4.9 4.9 0 0 1-1.266.603c-.991.31-2.44.38-3.064-.629A1.54 1.54 0 0 1 5 18V8a5 5 0 0 1 5-5Z");
}

.oad19bckv {
  d: path("M13 9h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2V7a1 1 0 0 1 2 0Z");
}

</style>
