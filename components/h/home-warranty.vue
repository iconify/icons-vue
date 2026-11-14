<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hybsqobpj"/><path class="nvvlslhxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-warranty" /></template>
<style>
.hybsqobpj {
  d: path("m12 2.5l1.553 1.204l1.947-.266l.743 1.819L18.062 6l-.266 1.947L19 9.5l-1.204 1.553l.266 1.947l-1.819.743l-.743 1.819l-1.947-.266L12 16.5l-1.553-1.204l-1.947.266l-.743-1.819L5.938 13l.266-1.947L5 9.5l1.204-1.553L5.938 6l1.819-.743l.743-1.819l1.947.266ZM9 16l-1.5 5.5l2-1.25L11 21.5l.5-4.5m3.5-1l1.5 5.5l-2-1.25L13 21.5l-.5-4.5");
}

.nvvlslhxw {
  d: path("m9 10l3-3l3 3v3H9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
