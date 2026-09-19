<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="uhx3m_1tm"/><path class="cnclnrbgj"/><path class="y9ta6ccsz"/><path class="d4_fizylv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:forcedoze" /></template>
<style>
.cnclnrbgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.169 20.765l-3.192 5.694c-.801 1.43-1.107 3.013-.033 3.851c1.132.884 2.646.44 3.318-.736l3.11-5.437h11.257m.844-17.554l-2.024 3.614");
}

.d4_fizylv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.315 15.499c.31.96 1.759.986 2.071 0m-6.701 0c-.31.96-1.759.986-2.071 0M8.5 24.137h4.78m21.44 0h4.78");
}

.uhx3m_1tm {
  width: 31px;
  height: 39px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.y9ta6ccsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.831 20.765l3.192 5.694c.801 1.43 1.107 3.013.033 3.851c-1.132.884-2.646.44-3.318-.736l-3.11-5.437m-14.437-3.62c-.455-7.232 3.097-11.13 8.809-11.13s9.264 3.898 8.81 11.13c-1.37 1.276-4.492 2.271-8.81 2.271s-7.44-.995-8.81-2.27zm2.336-13.934l2.024 3.614");
}

</style>
