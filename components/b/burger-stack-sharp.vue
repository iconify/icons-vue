<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="agcy0y53w"/><path class="nkwhnfxcf"/><path class="vih6mbbbp"/><path class="tdj0jgbft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:burger-stack-sharp" /></template>
<style>
.agcy0y53w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6.5a7.5 3.75 0 0 1 15 0v.75h-15z");
}

.nkwhnfxcf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 5h.01m4.99 0h.01");
}

.tdj0jgbft {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 13h8.25l1.25 1.75L14 13h6.75M4 18.75h16v2.5H4z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vih6mbbbp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 9.5h17.5v7H3.25z");
}

</style>
