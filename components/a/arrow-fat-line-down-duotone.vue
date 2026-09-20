<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ivyo50bpc"/><path class="ympe5qb6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-fat-line-down-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ivyo50bpc {
  d: path("m224 136l-96 96l-96-96h48V72h96v64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ympe5qb6t {
  d: path("M231.39 132.94A8 8 0 0 0 224 128h-40V72a8 8 0 0 0-8-8H80a8 8 0 0 0-8 8v56H32a8 8 0 0 0-5.66 13.66l96 96a8 8 0 0 0 11.32 0l96-96a8 8 0 0 0 1.73-8.72M128 220.69L51.31 144H80a8 8 0 0 0 8-8V80h80v56a8 8 0 0 0 8 8h28.69ZM72 40a8 8 0 0 1 8-8h96a8 8 0 0 1 0 16H80a8 8 0 0 1-8-8");
}

</style>
