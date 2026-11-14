<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="guqqttbir"/><path class="b6lj25bxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-export" /></template>
<style>
.b6lj25bxi {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m-1.5 10.25H16a1.5 1.5 0 0 0-1.5 1.5V20a1.5 1.5 0 0 0 1.5 1.5h3.75a1.5 1.5 0 0 0 1.5-1.5v-1.5m-3.5-.25l3.75-3.75m-2.75 0h2.75v2.75");
}

.guqqttbir {
  d: path("M3.5 3v17.5h8.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
