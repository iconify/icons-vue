<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="c3evw3_ke"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:burst-shape-sharp" /></template>
<style>
.c3evw3_ke {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.36 2.98l.95 1.23l.36.48l.53-.27l1.39-.71l.53-.27l.12.59l.32 1.52l.12.59l.6-.02l1.55-.03l.6-.01l-.15.58l-.38 1.5l-.14.59l.54.24l1.42.65l.54.25l-.38.46l-1 1.19l-.38.46l.38.46l1 1.19l.38.46l-.54.25l-1.42.65l-.54.24l.14.59l.38 1.5l.15.58l-.6-.01l-1.55-.03l-.6-.02l-.12.59l-.32 1.52l-.12.59l-.53-.27l-1.39-.71l-.53-.27l-.36.48l-.95 1.23l-.36.48l-.36-.48l-.95-1.23l-.36-.48l-.53.27l-1.39.71l-.53.27l-.12-.59l-.32-1.52l-.12-.59l-.6.02l-1.55.03l-.6.01l.15-.58l.38-1.5l.14-.59l-.54-.24l-1.42-.65l-.54-.25l.38-.46l1-1.19l.38-.46l-.38-.46l-1-1.19l-.38-.46l.54-.25l1.42-.65l.54-.24l-.14-.59l-.38-1.5l-.15-.58l.6.01l1.55.03l.6.02l.12-.59l.32-1.52l.12-.59l.53.27l1.39.71l.53.27l.36-.48l.95-1.23l.36-.48z");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
