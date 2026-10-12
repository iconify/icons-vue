<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jfjzqbsaf"/><path class="pwmo88bii"/><path class="xzx5mv78i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:keyboard-access-sharp" /></template>
<style>
.jfjzqbsaf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.25h18.5v11H2.75z");
}

.pwmo88bii {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 13.75h.01m3.49 0h.01m3.99 0h.01m3.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xzx5mv78i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 17.75h9m-12.75-12h11m-3-3l3 3l-3 3m6.5-6v6");
}

</style>
