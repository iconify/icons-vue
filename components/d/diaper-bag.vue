<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cwx_40u5s"/><path class="of_ixpzqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diaper-bag" /></template>
<style>
.cwx_40u5s {
  d: path("M4 9h16l-1 11a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 20Zm2.5 0V5.5a2 2 0 0 1 4 0V9m3 0V5.5a2 2 0 0 1 4 0V9");
}

.of_ixpzqs {
  d: path("M8 13.5h8v5H8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
