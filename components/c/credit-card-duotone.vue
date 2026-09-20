<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="txk7dfbxr"/><path class="r5n8sobdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:credit-card-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r5n8sobdl {
  d: path("M224 48H32a16 16 0 0 0-16 16v128a16 16 0 0 0 16 16h192a16 16 0 0 0 16-16V64a16 16 0 0 0-16-16m0 16v24H32V64Zm0 128H32v-88h192zm-16-24a8 8 0 0 1-8 8h-32a8 8 0 0 1 0-16h32a8 8 0 0 1 8 8m-64 0a8 8 0 0 1-8 8h-16a8 8 0 0 1 0-16h16a8 8 0 0 1 8 8");
}

.txk7dfbxr {
  d: path("M232 96v96a8 8 0 0 1-8 8H32a8 8 0 0 1-8-8V96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
