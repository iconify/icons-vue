<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="v-z23rbyj"/><path class="zecid-f6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:gas-pump-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.v-z23rbyj {
  d: path("M168 56v160H56V56a16 16 0 0 1 16-16h80a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zecid-f6u {
  d: path("m241 69.66l-19.34-19.32a8 8 0 0 0-11.32 11.32L229.66 81a8 8 0 0 1 2.34 5.63V168a8 8 0 0 1-16 0v-40a24 24 0 0 0-24-24h-16V56a24 24 0 0 0-24-24H72a24 24 0 0 0-24 24v152H32a8 8 0 0 0 0 16h160a8 8 0 0 0 0-16h-16v-88h16a8 8 0 0 1 8 8v40a24 24 0 0 0 48 0V86.63a23.85 23.85 0 0 0-7-16.97M64 208V56a8 8 0 0 1 8-8h80a8 8 0 0 1 8 8v152Zm80-96a8 8 0 0 1-8 8H88a8 8 0 0 1 0-16h48a8 8 0 0 1 8 8");
}

</style>
