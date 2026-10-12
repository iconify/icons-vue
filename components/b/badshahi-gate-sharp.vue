<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y7r63jbem"/><path class="k_i2081zh"/><path class="kehygs9mj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:badshahi-gate-sharp" /></template>
<style>
.k_i2081zh {
  d: path("M6.5 21.25v-9h11v9");
}

.kehygs9mj {
  d: path("M9.75 21.25v-6.13L12 13.5l2.25 1.62v6.13");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7r63jbem {
  d: path("M4.5 9.25a1.5 2.5 0 0 1 3 0Zm5.5 0a2 3 0 0 1 4 0Zm6.5 0a1.5 2.5 0 0 1 3 0Zm-13.25 0h17.5v12H3.25z");
}

</style>
