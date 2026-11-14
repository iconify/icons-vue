<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ozx59q5us"/><path class="zjev8eomi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:luggage-cart-hotel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ozx59q5us {
  d: path("M3.5 2.5H6v15h14.5");
}

.zjev8eomi {
  d: path("M4.25 19.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m8-14.25h4.5a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 16.75 10h-4.5a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 12.25 5m-.625 5h5.75A2.625 2.625 0 0 1 20 12.625v2.25a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 9 14.875v-2.25A2.625 2.625 0 0 1 11.625 10");
}

</style>
