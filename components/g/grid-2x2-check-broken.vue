<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="taogqpb9g"/><path class="fq2i0fpuc"/><path class="frr67dw0i"/><path class="noodpccbe"/><path class="vhw97bcth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-check-broken" /></template>
<style>
.fq2i0fpuc {
  d: path("M21.9996 12C21.9996 7.28597 21.9996 4.92894 20.5352 3.46448");
}

.frr67dw0i {
  stroke-linejoin: round;
  d: path("M14.5 17.7295L16.6 20.2295L20.5 15.2295");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.noodpccbe {
  d: path("M22 12H10M6 12H2");
}

.taogqpb9g {
  d: path("M16.5501 2.08856C15.3375 2 13.8503 2 12 2C7.28595 2 4.92893 2 3.46447 3.46447C2 4.92893 2 7.28595 2 12C2 16.714 2 19.0711 3.46447 20.5355C4.92893 22 7.28595 22 12 22");
}

.vhw97bcth {
  d: path("M12.0049 22.005V2.005");
}

</style>
