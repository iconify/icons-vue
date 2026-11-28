<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="eoc_75btw"/><path class="d7dwsj__a"/><path clip-rule="evenodd" class="f-q89ibyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-alert-sharp-fill" /></template>
<style>
.d7dwsj__a {
  d: path("M8 2V8M16 2V8M18 14V18");
}

.eoc_75btw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 4H21C21.552 4 22 4.448 22 5V11C22 11.552 21.552 12 21 12H12V21C12 21.552 11.552 22 11 22H3C2.448 22 2 21.552 2 21V5C2 4.448 2.448 4 3 4ZM6 10V12H18V10H6Z");
  stroke: none;
}

.f-q89ibyd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 20C18.552 20 19 20.448 19 21C19 21.552 18.552 22 18 22C17.448 22 17 21.552 17 21C17 20.448 17.448 20 18 20Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
