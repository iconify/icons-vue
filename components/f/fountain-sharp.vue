<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="js370q7xg"/><path clip-rule="evenodd" class="s_ly95b4x"/><path clip-rule="evenodd" class="u0sp4eb6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fountain-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.js370q7xg {
  d: path("M13 18V6C13 3.79 14.791 2 17 2C19.209 2 21 3.79 21 6V7M13 16V10C13 7.79 11.209 6 9 6C6.791 6 5 7.79 5 10V11M3 18H21C21.552 18 22 18.45 22 19C22 20.66 20.657 22 19 22H5C3.343 22 2 20.66 2 19C2 18.45 2.448 18 3 18Z");
}

.s_ly95b4x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 14C4 14.55 3.552 15 3 15C2.448 15 2 14.55 2 14C2 13.45 2.448 13 3 13C3.552 13 4 13.45 4 14ZM8 14C8 14.55 7.552 15 7 15C6.448 15 6 14.55 6 14C6 13.45 6.448 13 7 13C7.552 13 8 13.45 8 14ZM22 10C22 10.55 21.552 11 21 11C20.448 11 20 10.55 20 10C20 9.45 20.448 9 21 9C21.552 9 22 9.45 22 10Z");
  stroke: none;
}

.u0sp4eb6g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 12.5C19 13.05 18.552 13.5 18 13.5C17.448 13.5 17 13.05 17 12.5C17 11.95 17.448 11.5 18 11.5C18.552 11.5 19 11.95 19 12.5ZM23 14C23 14.55 22.552 15 22 15C21.448 15 21 14.55 21 14C21 13.45 21.448 13 22 13C22.552 13 23 13.45 23 14Z");
  stroke: none;
}

</style>
