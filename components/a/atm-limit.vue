<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l0k9nypas"/><path class="x_-tjnb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-limit" /></template>
<style>
.l0k9nypas {
  d: path("M13.6 21.5H4v-19h16v9.4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x_-tjnb9x {
  d: path("M7 5h10v6H7Zm-.5 8.75h5.7m-5.45 3.5h.01m2.49 0h.01m2.49 0h.01m3.24-2.5h6m-3 6.75v-4m-2.25 2.25L18 17.5l2.25 2.25");
}

</style>
