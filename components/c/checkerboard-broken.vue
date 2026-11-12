<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qg9qewbnt"/><path class="njn_u_akb"/><path class="rxtpsp2pz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:checkerboard-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.njn_u_akb {
  d: path("M12 2V12M12 12V22M12 12H2M12 12H22");
}

.qg9qewbnt {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.286 22 4.9289 22 3.4645 20.5355C2 19.0711 2 16.714 2 12C2 7.286 2 4.9289 3.4645 3.4645C4.9289 2 7.286 2 12 2C16.714 2 19.0711 2 20.5355 3.4645C21.5093 4.4382 21.8356 5.8066 21.9449 8");
}

.rxtpsp2pz {
  d: path("M21.9949 14.0052L14.0053 21.9947M12.0001 18.5L18.5001 12M2.00537 9.99482L9.99487 2.00525M12.0001 5.49999L5.50012 12.0001");
}

</style>
