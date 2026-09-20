<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="legzizgkh"/><path class="y2-j-5blk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:door-open-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.legzizgkh {
  d: path("M200 40v184h-32V32h24a8 8 0 0 1 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y2-j-5blk {
  d: path("M232 216h-24V40a16 16 0 0 0-16-16H64a16 16 0 0 0-16 16v176H24a8 8 0 0 0 0 16h208a8 8 0 0 0 0-16m-40 0h-16V40h16ZM64 40h96v176H64Zm80 92a12 12 0 1 1-12-12a12 12 0 0 1 12 12");
}

</style>
