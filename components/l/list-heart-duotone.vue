<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="rrrcr6bka"/><path class="koug14iyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:list-heart-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.koug14iyk {
  d: path("M32 64a8 8 0 0 1 8-8h176a8 8 0 0 1 0 16H40a8 8 0 0 1-8-8m8 72h64a8 8 0 0 0 0-16H40a8 8 0 0 0 0 16m80 48H40a8 8 0 0 0 0 16h80a8 8 0 0 0 0-16m128-40c0 36.52-50.28 62.08-52.42 63.16a8 8 0 0 1-7.16 0C186.28 206.08 136 180.52 136 144a32 32 0 0 1 56-21.14A32 32 0 0 1 248 144m-16 0a16 16 0 0 0-32 0a8 8 0 0 1-16 0a16 16 0 0 0-32 0c0 20.18 26.21 39.14 40 46.93c13.79-7.78 40-26.74 40-46.93");
}

.rrrcr6bka {
  d: path("M240 144c0 32-48 56-48 56s-48-24-48-56a24 24 0 0 1 48 0a24 24 0 0 1 48 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
