<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sgjbtc6qp"/><path class="dn5dzgofz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hot-milk" /></template>
<style>
.dn5dzgofz {
  d: path("M10 11.25s-2 2.25-2 3.5a2 2 0 0 0 4 0c0-1.25-2-3.5-2-3.5Zm-1.5-5.5C7.75 5 9.25 4 8.5 3m3 2.75C10.75 5 12.25 4 11.5 3");
}

.sgjbtc6qp {
  d: path("M4.5 8h11v9a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 17Zm11 2H17a2.5 2.5 0 0 1 0 5h-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
