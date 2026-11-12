<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qvvaxwgmr"/><path class="kf3dhdbcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-square-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kf3dhdbcu {
  d: path("M2 7V3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

.qvvaxwgmr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.342 9.06l11 4a1.002 1.002 0 0 1 .029 1.868l-4.602 1.841l-1.841 4.602a1 1 0 0 1-1.868-.029l-4-11a1 1 0 0 1 1.282-1.282");
}

</style>
