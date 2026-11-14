<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="es4du_bag"/><path class="hs0n8kbwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:entrance-sign" /></template>
<style>
.es4du_bag {
  d: path("M3 3h18v11H3Zm9 11v7.5m-5.5-13h10.25");
}

.hs0n8kbwk {
  d: path("m14 5.75l2.75 2.75L14 11.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
