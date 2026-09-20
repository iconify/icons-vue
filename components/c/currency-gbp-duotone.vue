<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="fd2l-9bxq"/><path class="t-9h-4bbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:currency-gbp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fd2l-9bxq {
  d: path("M168 208H60a36 36 0 0 0 36-36V84a44 44 0 0 1 72-33.95Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t-9h-4bbq {
  d: path("M192 208a8 8 0 0 1-8 8H56a8 8 0 0 1 0-16h4a28 28 0 0 0 28-28v-36H56a8 8 0 0 1 0-16h32V84a52 52 0 0 1 85.08-40.12a8 8 0 1 1-10.18 12.34A36 36 0 0 0 104 84v36h32a8 8 0 0 1 0 16h-32v36a43.82 43.82 0 0 1-10.08 28H184a8 8 0 0 1 8 8");
}

</style>
