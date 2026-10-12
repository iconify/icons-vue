<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="llqzir1_l"/><path class="npjn27n1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:candle-spa-sharp" /></template>
<style>
.llqzir1_l {
  d: path("M12 2.75c1.4 1.5 2.2 2.7 2.2 3.85a2.2 2.2 0 0 1-4.4 0c0-1.15.8-2.35 2.2-3.85Zm0 7.5v2M4.75 13h14.5v8.25H4.75z");
}

.npjn27n1y {
  d: path("M4.75 16.25c2.4.9 4.8.9 7.25 0s4.85-.9 7.25 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
