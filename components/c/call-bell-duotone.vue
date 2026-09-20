<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="fux4j1bdo"/><path class="c8hbx8ktz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:call-bell-duotone" /></template>
<style>
.c8hbx8ktz {
  d: path("M24 184h208a8 8 0 0 0 0-16h-8v-16a96.12 96.12 0 0 0-88-95.66V40h16a8 8 0 0 0 0-16h-48a8 8 0 0 0 0 16h16v16.34A96.12 96.12 0 0 0 32 152v16h-8a8 8 0 0 0 0 16m24-32a80 80 0 0 1 160 0v16H48Zm192 56a8 8 0 0 1-8 8H24a8 8 0 0 1 0-16h208a8 8 0 0 1 8 8");
}

.cuyn6tgcc {
  fill: currentColor;
}

.fux4j1bdo {
  d: path("M216 152v24H40v-24a88 88 0 0 1 176 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
