<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="s6vpnyndj"/><path class="lqi-0mugw"/><path clip-rule="evenodd" class="l4wjw054o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-alert-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l4wjw054o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 20C20 20.552 19.552 21 19 21C18.448 21 18 20.552 18 20C18 19.448 18.448 19 19 19C19.552 19 20 19.448 20 20Z");
  stroke: none;
}

.lqi-0mugw {
  d: path("M13 20H2V4H22V11M2 7L11.293 11C11.715 11.282 12.285 11.282 12.707 11L22 7M19 13V17");
}

.s6vpnyndj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4H19C20.657 4 22 5.343 22 7L12.707 11C12.285 11.282 11.715 11.282 11.293 11L2 7C2 5.343 3.343 4 5 4Z");
  stroke: none;
}

</style>
