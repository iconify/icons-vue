<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bauwzxbvg"/><path class="tp7u0ubgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinema-hall" /></template>
<style>
.bauwzxbvg {
  d: path("M2.5 3.5h19V10h-19Zm2 6.5v10.5h15V10M7 6.75h.01m4.99 0h.01m4.99 0h.01");
}

.tp7u0ubgd {
  d: path("M9.5 20.5v-7h5v7m-2.5-7v7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
