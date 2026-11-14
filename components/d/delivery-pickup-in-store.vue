<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o-e57w2tl"/><path class="mgza4_bhu"/><path class="znz31wb9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-pickup-in-store" /></template>
<style>
.mgza4_bhu {
  d: path("M12 11.25L15 13v3.5l-3 1.75l-3-1.75V13Z");
}

.o-e57w2tl {
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0M5.25 8.75V18m13.5-9.25V18M3.5 18h17v3h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.znz31wb9z {
  d: path("m9 13l3 1.75L15 13m-3 1.75v3.5");
}

</style>
