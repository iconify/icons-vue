<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="u8m7_5qws"/><path class="ifhaxr7hi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-fat-line-up-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ifhaxr7hi {
  d: path("m229.66 114.34l-96-96a8 8 0 0 0-11.32 0l-96 96A8 8 0 0 0 32 128h40v56a8 8 0 0 0 8 8h96a8 8 0 0 0 8-8v-56h40a8 8 0 0 0 5.66-13.66M176 112a8 8 0 0 0-8 8v56H88v-56a8 8 0 0 0-8-8H51.31L128 35.31L204.69 112Zm8 104a8 8 0 0 1-8 8H80a8 8 0 0 1 0-16h96a8 8 0 0 1 8 8");
}

.u8m7_5qws {
  d: path("M224 120h-48v64H80v-64H32l96-96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
