<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d7birxsaj"/><path class="wygbjlloz"/><path class="xr9fg6b7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calculated-column" /></template>
<style>
.d7birxsaj {
  d: path("M12.9 21H3V3h18v11.1M9 3v18m6-18v9.6M3 9h18M3 15h8.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wygbjlloz {
  fill: currentColor;
  d: path("M15 3h4a2 2 0 0 1 2 2v6h-6Z");
}

.xr9fg6b7l {
  d: path("M17.25 14.5q-1.5 0-1.5 1.5v5.5m-1.25-4h2.75m1 .25l3.25 3.75m0-3.75l-3.25 3.75");
}

</style>
