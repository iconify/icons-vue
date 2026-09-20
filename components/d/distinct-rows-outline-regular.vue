<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="avcp11bgx"/><path class="iiq-sr0bx"/><path class="ytp_psb3u"/><path class="nvzooz8re"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:distinct-rows-outline-regular" /></template>
<style>
.avcp11bgx {
  d: path("M2 5.5A2.5 2.5 0 0 1 4.5 3h3A2.5 2.5 0 0 1 10 5.5 2.5 2.5 0 0 1 7.5 8h-3A2.5 2.5 0 0 1 2 5.5");
}

.iiq-sr0bx {
  d: path("M14 5.5A2.5 2.5 0 0 1 16.5 3h3A2.5 2.5 0 0 1 22 5.5 2.5 2.5 0 0 1 19.5 8h-3A2.5 2.5 0 0 1 14 5.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvzooz8re {
  d: path("M4 18.5A2.5 2.5 0 0 1 6.5 16h11a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-11A2.5 2.5 0 0 1 4 18.5");
}

.ytp_psb3u {
  d: path("m6 8 6 6 6 -6");
}

</style>
