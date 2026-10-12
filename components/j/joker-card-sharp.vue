<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="s5cqcmbxe"/><path class="p4k1-xohv"/><path class="zc_41vubh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:joker-card-sharp" /></template>
<style>
.p4k1-xohv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 18H17v-6.5l-.56.5l-1.38 1.25l-.56.5l-.46-.59l-1.58-2.07l-.46-.59l-.46.59l-1.58 2.07l-.46.59l-.56-.5L7.56 12L7 11.5V18z");
}

.s5cqcmbxe {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h16.5v18.5H3.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zc_41vubh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 9h.01M17 9h.01M12 8h.01");
}

</style>
