<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cudpy66uo"/><path class="bywjbpn-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flight-attendant" /></template>
<style>
.bywjbpn-g {
  d: path("m10.083 3.346l2.69-.572a1.375 1.375 0 0 1 1.631 1.059a1.375 1.375 0 0 1-1.059 1.631l-2.69.572a1.375 1.375 0 0 1-1.631-1.059a1.375 1.375 0 0 1 1.059-1.631M4 21.5c0-3.75 3.5-5.75 8-5.75q.286 0 .565.011m7.556.118l-4.596 4.596m-.177-4.066l3.359.884l.884 3.359m-4.773-1.238l1.768 1.768");
}

.cudpy66uo {
  d: path("M8.5 9.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
