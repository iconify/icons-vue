<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="acf0b3yhr"/><path class="qj5c40ohq"/><path class="k4dvy49ve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ice-cream-cone-broken" /></template>
<style>
.acf0b3yhr {
  d: path("M7.9218 3.47297C9.0548 2.61267 10.4678 2.10217 12 2.10217C15.7279 2.10217 18.75 5.12427 18.75 8.85217C18.75 10.3022 18.1 11.1022 17 11.1022H7C5.9 11.1022 5.25 10.3022 5.25 8.85217C5.25 7.87557 5.4574 6.94747 5.8305 6.10937");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4dvy49ve {
  d: path("M9.20117 15.7022L15.7324 13.5023");
}

.qj5c40ohq {
  d: path("M7.25 11.1022L11.4143 20.9213L11.4144 20.9214C11.6904 21.5722 11.8285 21.8978 12 21.8978C12.1715 21.8978 12.3096 21.5722 12.5856 20.9214L12.5857 20.9213L16.75 11.1022");
}

</style>
