<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="y9pqy9ioq"/><path class="rzfv52xrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chart-pie-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rzfv52xrf {
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m71.87 53.27L136 114.14V40.37a88 88 0 0 1 63.87 36.9M120 40.37v83l-71.89 41.5A88 88 0 0 1 120 40.37M128 216a88 88 0 0 1-71.87-37.27l151.76-87.61A88 88 0 0 1 128 216");
}

.y9pqy9ioq {
  d: path("M128 32v96l-83.14 48A96 96 0 0 1 128 32");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
