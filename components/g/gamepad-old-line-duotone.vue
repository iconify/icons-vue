<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVG6WNJNcPe)" class="caog0qvka"><path class="xpv-mabyq"/><path class="z9n9raclw"/><path class="hxi5c3b8i"/><path class="opfsj7bhx"/><path class="t-lavp4nf"/></g><defs><clipPath id="SVG6WNJNcPe"><rect class="fng6irbns"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-old-line-duotone" /></template>
<style>
.caog0qvka {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.fng6irbns {
  width: 24px;
  height: 24px;
  fill: var(--svg-color--fff, #fff);
}

.ft5dv1b6b {
  fill: none;
}

.hxi5c3b8i {
  d: path("M2 12C2 9.19974 2 7.79961 2.54497 6.73005C3.02433 5.78924 3.78924 5.02433 4.73005 4.54497C5.79961 4 7.19974 4 10 4H14C16.8003 4 18.2004 4 19.27 4.54497C20.2108 5.02433 20.9757 5.78924 21.455 6.73005C22 7.79961 22 9.19974 22 12C22 14.8003 22 16.2004 21.455 17.27C20.9757 18.2108 20.2108 18.9757 19.27 19.455C18.2004 20 16.8003 20 14 20H10C7.19974 20 5.79961 20 4.73005 19.455C3.78924 18.9757 3.02433 18.2108 2.54497 17.27C2 16.2004 2 14.8003 2 12Z");
}

.opfsj7bhx {
  stroke-linejoin: round;
  d: path("M15 10.5H15.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.t-lavp4nf {
  stroke-linejoin: round;
  d: path("M17 13.5H17.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xpv-mabyq {
  d: path("M8 10V12M8 12V14M8 12H6M8 12L10 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.z9n9raclw {
  d: path("M12 4V3C12 2.44772 12.4477 2 13 2H14C14.5523 2 15 1.55228 15 1V0");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
