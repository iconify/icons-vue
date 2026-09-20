<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="gj4xuecta"/><path class="x3icy5bhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-down-left-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gj4xuecta {
  d: path("M80 120v96l-48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x3icy5bhc {
  d: path("M168 48H80a8 8 0 0 0 0 16h88a48 48 0 0 1 0 96H88v-40a8 8 0 0 0-13.66-5.66l-48 48a8 8 0 0 0 0 11.32l48 48A8 8 0 0 0 88 216v-40h80a64 64 0 0 0 0-128M72 196.69L43.31 168L72 139.31Z");
}

</style>
