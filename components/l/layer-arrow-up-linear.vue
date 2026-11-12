<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h8npn_pir"/><path class="q70sseccx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layer-arrow-up-linear" /></template>
<style>
.h8npn_pir {
  d: path("M7.7873 13.192L4.9788 14.315C2.9929 15.109 2 15.506 2 16C2 16.494 2.9929 16.891 4.9788 17.685L7.7873 18.808C9.7732 19.603 10.7661 20 12 20C13.2339 20 14.2268 19.603 16.2127 18.808L19.0212 17.685C21.0071 16.891 22 16.494 22 16C22 15.506 21.0071 15.109 19.0212 14.315L16.2127 13.192");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q70sseccx {
  stroke-linejoin: round;
  d: path("M12 16V4M15 7L12 4L9 7");
}

</style>
