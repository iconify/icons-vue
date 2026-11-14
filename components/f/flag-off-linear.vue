<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wsswtccxx"/><path class="x-2r17btl"/><path class="kez1s6byc"/><path class="irp_i5_gp"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flag-off-linear" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irp_i5_gp {
  d: path("M17.7646 14.3089L17.9365 14.2659C18.5616 14.1096 19.0001 13.548 19.0001 12.9037V5.53672C19.0001 4.75612 18.2666 4.18342 17.5093 4.37272C15.8781 4.78052 14.1598 4.66392 12.5987 4.03942L12.395 3.95802C10.8322 3.33282 9.12129 3.17582 7.47079 3.50592L7.04639 3.59072");
}

.kez1s6byc {
  d: path("M5 14L7.4707 13.5059C9.1212 13.1758 10.8321 13.3328 12.3949 13.958C13.0772 14.2309 13.787 14.4144 14.5073 14.5073");
}

.wsswtccxx {
  d: path("M5 22V14");
}

.x-2r17btl {
  d: path("M5 14V5");
}

</style>
