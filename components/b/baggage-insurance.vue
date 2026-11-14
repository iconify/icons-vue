<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o_od18b_v"/><path class="n05k6hbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baggage-insurance" /></template>
<style>
.n05k6hbis {
  d: path("m18.5 14.25l3.25 1.25V18c0 2-1.5 3.25-3.25 4c-1.75-.75-3.25-2-3.25-4v-2.5Z");
}

.o_od18b_v {
  d: path("M12.9 20.5H2.5V7h17v4.6M8.5 7V5A1.5 1.5 0 0 1 10 3.5h2A1.5 1.5 0 0 1 13.5 5v2M6.25 7v13.5M15.75 7v5.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
