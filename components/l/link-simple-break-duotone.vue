<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hnrl0t8yo"/><path class="b2fr0ow0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:link-simple-break-duotone" /></template>
<style>
.b2fr0ow0y {
  d: path("M232 80a55.67 55.67 0 0 1-16.4 39.6l-30.07 30.06a8 8 0 0 1-11.31-11.32l30.07-30.06a40 40 0 1 0-56.57-56.56l-30.06 30.05a8 8 0 0 1-11.32-11.32L136.4 40.4A56 56 0 0 1 232 80m-93.66 94.22l-30.06 30.06a40 40 0 1 1-56.56-56.57l30.05-30.05a8 8 0 0 0-11.32-11.32L40.4 136.4a56 56 0 0 0 79.2 79.2l30.06-30.07a8 8 0 0 0-11.32-11.31");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hnrl0t8yo {
  d: path("m209.94 113.94l-96 96a48 48 0 0 1-67.88-67.88l96-96a48 48 0 0 1 67.88 67.88");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
