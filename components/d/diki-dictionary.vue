<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zdmc9jkkv"/><circle class="sbd3khbbl"/><path class="krhhq7b1z"/><circle class="r093cpoin"/><path class="hpgjfw8ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diki-dictionary" /></template>
<style>
.hpgjfw8ft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.439 21.185l-.269 7.888m-16.183-6.954a2.979 2.979 0 0 0-5.757-1.53l-.497 1.872a2.979 2.979 0 0 0 5.758 1.53m-.765 2.878l3.058-11.515");
}

.krhhq7b1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.2 19.445l-.814 7.851");
}

.r093cpoin {
  cx: 34.564px;
  cy: 17.538px;
  r: 0.75px;
  fill: currentColor;
}

.sbd3khbbl {
  cx: 22.577px;
  cy: 15.816px;
  r: 0.75px;
  fill: currentColor;
}

.zdmc9jkkv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.306 28.352c-4.354-3.653-8.193-9.449.024-15.447C22.966 2.95 50.903 18.714 41.663 28.99c-8.95 9.954-25.322 3.69-26.355 3.284c-.96 3.271-.468 5.99-.468 5.99c-5.411-4.588-5.559-9.016-5.534-9.913m18.543-13.549l-3.058 11.515m.651-2.446l6.59-3.802m-4.493 2.592l3.014 5.168");
}

</style>
