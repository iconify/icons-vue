<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="rcd9asbdv"/><path class="wst1xbc7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:dots-three-vertical-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rcd9asbdv {
  d: path("M176 32v192a16 16 0 0 1-16 16H96a16 16 0 0 1-16-16V32a16 16 0 0 1 16-16h64a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wst1xbc7b {
  d: path("M140 128a12 12 0 1 1-12-12a12 12 0 0 1 12 12m-12-56a12 12 0 1 0-12-12a12 12 0 0 0 12 12m0 112a12 12 0 1 0 12 12a12 12 0 0 0-12-12");
}

</style>
