<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="lkpv7-y7d"/><path class="d-yq76bkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-down-left-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d-yq76bkf {
  d: path("M224 48a8 8 0 0 0-8 8a88.1 88.1 0 0 1-88 88H88v-40a8 8 0 0 0-13.66-5.66l-48 48a8 8 0 0 0 0 11.32l48 48A8 8 0 0 0 88 200v-40h40A104.11 104.11 0 0 0 232 56a8 8 0 0 0-8-8M72 180.69L43.31 152L72 123.31Z");
}

.lkpv7-y7d {
  d: path("M80 104v96l-48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
