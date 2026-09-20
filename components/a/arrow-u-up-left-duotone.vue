<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="p54zh3bvi"/><path class="ps9b6vbhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-up-left-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p54zh3bvi {
  d: path("M80 40v96L32 88Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ps9b6vbhm {
  d: path("M168 80H88V40a8 8 0 0 0-13.66-5.66l-48 48a8 8 0 0 0 0 11.32l48 48A8 8 0 0 0 88 136V96h80a48 48 0 0 1 0 96H80a8 8 0 0 0 0 16h88a64 64 0 0 0 0-128m-96 36.69L43.31 88L72 59.31Z");
}

</style>
