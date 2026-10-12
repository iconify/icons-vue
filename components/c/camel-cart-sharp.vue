<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zar-cvxmb"/><circle class="e3ijufb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camel-cart-sharp" /></template>
<style>
.e3ijufb_j {
  cx: 5.5px;
  cy: 19.25px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zar-cvxmb {
  d: path("m11.89 11.42l.57-.71l.64-.77l.71-.21l.72-.2l.82.51q.82.51 1.44 1.12l.61.62l.42-.91l.19-.43l.42-.91l.41-.41l.4-.41l.82.1l.82.1l.1.41l.11.41l-.61.31l-.62.31l-.31.92l-.31.92l-.6.8l-.02.04l-.6.8h-5.95l-.41-.82l-.41-.82zm1 2.41V20m4.72-6.17V20m-9.36-7h3.25m-8.75-1.5h5.5v3h-5.5z");
}

</style>
