<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ezm29kb8o"/><path class="kr2eaebsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-up-left-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ezm29kb8o {
  d: path("m168 48l-96 96V48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kr2eaebsq {
  d: path("M232 208a8 8 0 0 1-8 8H48a8 8 0 0 1 0-16h176a8 8 0 0 1 8 8M64 144V48a8 8 0 0 1 8-8h96a8 8 0 0 1 5.66 13.66L131.31 96l58.35 58.34a8 8 0 0 1-11.32 11.32L120 107.31l-42.34 42.35A8 8 0 0 1 64 144m16-19.31l34.34-34.35L148.69 56H80Z");
}

</style>
