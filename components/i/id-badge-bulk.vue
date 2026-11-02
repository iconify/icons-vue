<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ygqlu6xwg"/><path class="yk1y2wb-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:id-badge-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ygqlu6xwg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3Z");
}

.yk1y2wb-t {
  d: path("M10 5h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m-1 7a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-3 9a4 4 0 0 1 8 0a1 1 0 0 1-2 0a2 2 0 0 0-4 0a1 1 0 0 1-2 0");
}

</style>
