<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wrib16b3z"/><path class="abn59i1vt"/><path class="vrkygjb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:copier-sharp" /></template>
<style>
.abn59i1vt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 9.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vrkygjb0p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 15h11v3.25h-11z");
}

.wrib16b3z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h16.5v2.5H3.75zm-1 5h18.5v13.5H2.75zm0 4h18.5");
}

</style>
