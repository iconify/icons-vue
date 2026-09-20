<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGEoNrkDrm)" class="r4i437pya"/><path class="uzaqc3b2d"/></g><defs><linearGradient id="SVGEoNrkDrm" x1="19.228" x2="4.903" y1="18.9" y2="20.437" gradientUnits="userSpaceOnUse"><stop class="i8-r8cnua"/><stop offset="1" class="yvbqngq-h"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:euno-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i8-r8cnua {
  stop-color: var(--svg-color--7599f2, #7599f2);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.uzaqc3b2d {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.836 8.125h10.47a1.03 1.03 0 0 0 .754-.325l1.678-1.74l.175-.18c.671-.693.197-1.88-.748-1.88H5.835c-.283 0-.552.114-.753.32c-.196.207-.31.49-.31.78v1.93c0 .29.114.569.31.775c.201.207.47.325.754.325zm12.329 2.065H5.835a1.08 1.08 0 0 0-.753.31a1.04 1.04 0 0 0-.31.733v7.724a1.03 1.03 0 0 0 .31.738c.201.197.47.305.754.305h6.474c.284 0 .552-.108.754-.31l1.858-1.828c.672-.655.202-1.476-.748-1.476H8.903v-2.592H16.3c.284 0 .552-.113.754-.31l1.683-1.337l.175-.17c.671-.661.197-1.786-.748-1.786");
}

.yvbqngq-h {
  stop-color: var(--svg-color--562cdd, #562cdd);
}

</style>
