<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="q7hlv-b5d"/><path class="oiainhp5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-up-right-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oiainhp5r {
  d: path("M172.94 143.39a8 8 0 0 0 8.72-1.73l48-48a8 8 0 0 0 0-11.32l-48-48A8 8 0 0 0 168 40v40H88a64 64 0 0 0 0 128h88a8 8 0 0 0 0-16H88a48 48 0 0 1 0-96h80v40a8 8 0 0 0 4.94 7.39M184 59.31L212.69 88L184 116.69Z");
}

.q7hlv-b5d {
  d: path("m224 88l-48 48V40Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
