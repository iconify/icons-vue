<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xi7qryb_x"/><path class="ek0gujbin"/><circle class="wft9rcgmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:evidence-bag-sharp" /></template>
<style>
.ek0gujbin {
  d: path("M7.6 13.5h5v4.25h-6V13.5zm7.9-5.75L17.69 6");
}

.wft9rcgmo {
  cx: 19.25px;
  cy: 4.75px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xi7qryb_x {
  d: path("M3.75 7.75H15.5l1.042-.001L16.5 8.79L16 18.5v2.75H3.25V18.5l-.5-9.71l-.042-1.041zM2.9 10.5h13.5");
}

</style>
