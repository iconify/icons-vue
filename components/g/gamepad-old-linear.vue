<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVG6WNJNcPe)" class="caog0qvka"><path class="ps7dwubep"/><path class="v5l5vgbks"/><path class="tr55gabkt"/><path class="e_un4ubpg"/><path class="xkvin1h0r"/></g><defs><clipPath id="SVG6WNJNcPe"><rect class="fng6irbns"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-old-linear" /></template>
<style>
.caog0qvka {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.e_un4ubpg {
  stroke-linejoin: round;
  d: path("M15 10.5H15.0001");
}

.fng6irbns {
  width: 24px;
  height: 24px;
  fill: var(--svg-color--fff, #fff);
}

.ft5dv1b6b {
  fill: none;
}

.ps7dwubep {
  d: path("M8 10V12M8 12V14M8 12H6M8 12L10 12");
}

.tr55gabkt {
  d: path("M10 20H14C16.8003 20 18.2004 20 19.27 19.455C20.2108 18.9757 20.9757 18.2108 21.455 17.27C22 16.2004 22 14.8003 22 12C22 9.19974 22 7.79961 21.455 6.73005C20.9757 5.78924 20.2108 5.02433 19.27 4.54497C18.2004 4 16.8003 4 14 4H10C7.19974 4 5.79961 4 4.73005 4.54497C3.78924 5.02433 3.02433 5.78924 2.54497 6.73005C2 7.79961 2 9.19974 2 12C2 14.8003 2 16.2004 2.54497 17.27C3.02433 18.2108 3.78924 18.9757 4.73005 19.455C5.79961 20 7.19974 20 10 20Z");
}

.v5l5vgbks {
  d: path("M12 4V3C12 2.44772 12.4477 2 13 2H14C14.5523 2 15 1.55228 15 1V0");
}

.xkvin1h0r {
  stroke-linejoin: round;
  d: path("M17 13.5H17.0001");
}

</style>
