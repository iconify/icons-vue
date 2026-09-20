<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="osgezcc-u"/><path class="m2152d-4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-down-right-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m2152d-4a {
  d: path("M195.06 80.61a8 8 0 0 0-8.72 1.73L140 128.69L69.66 58.34a8 8 0 0 0-11.32 11.32L128.69 140l-46.35 46.34A8 8 0 0 0 88 200h104a8 8 0 0 0 8-8V88a8 8 0 0 0-4.94-7.39M184 184h-76.69l38.34-38.34L184 107.31Z");
}

.osgezcc-u {
  d: path("M192 88v104H88Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
