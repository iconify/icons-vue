<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k0c74xblo"/><circle class="zgdxchwpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baseball-glove-sharp" /></template>
<style>
.k0c74xblo {
  d: path("M8.5 21.25v-13a5.5 5.5 0 0 1 11 0v13H18ZM12.25 5.5v3.75m3.5-3.75v3.75m-7.25 9h11M8.5 16l-4.1-5.35l-.961-1.452l2.7-2.2L7.1 8.45L8.5 10");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zgdxchwpj {
  cx: 14px;
  cy: 13.25px;
  r: 2px;
}

</style>
