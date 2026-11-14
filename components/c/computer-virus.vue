<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iau37ab1m"/><path class="u71s0_byq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:computer-virus" /></template>
<style>
.iau37ab1m {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8");
}

.u71s0_byq {
  d: path("M9.5 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm4.25-1.75l1-1m-1 4.5l1 1m-4.5-4.5l-1-1m1 4.5l-1 1M14.5 10H16m-6.5 0H8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
