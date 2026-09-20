<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="t1o67yb2j"/><path class="aow7t_blf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:align-left-duotone" /></template>
<style>
.aow7t_blf {
  d: path("M216 136H80a16 16 0 0 0-16 16v40a16 16 0 0 0 16 16h136a16 16 0 0 0 16-16v-40a16 16 0 0 0-16-16m0 56H80v-40h136zM48 40v176a8 8 0 0 1-16 0V40a8 8 0 0 1 16 0m32 80h96a16 16 0 0 0 16-16V64a16 16 0 0 0-16-16H80a16 16 0 0 0-16 16v40a16 16 0 0 0 16 16m0-56h96v40H80Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.t1o67yb2j {
  d: path("M72 104V64a8 8 0 0 1 8-8h96a8 8 0 0 1 8 8v40a8 8 0 0 1-8 8H80a8 8 0 0 1-8-8m144 40H80a8 8 0 0 0-8 8v40a8 8 0 0 0 8 8h136a8 8 0 0 0 8-8v-40a8 8 0 0 0-8-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
