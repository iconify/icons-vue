<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ueb-dyb6v"/><path class="ggc6lnvpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jib-camera-broadcast" /></template>
<style>
.ggc6lnvpn {
  d: path("M20.329 5.085L20.5 5a.69.69 0 0 1 1 .618v2.264a.69.69 0 0 1-1 .618l-.171-.085a1.5 1.5 0 0 1-.829-1.342v-.646a1.5 1.5 0 0 1 .829-1.342");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ueb-dyb6v {
  d: path("m3 18l12-9m-8 6l-3 6.5M7 15l3 6.5m5.75-17h2a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 17.75 9h-2A1.75 1.75 0 0 1 14 7.25v-1a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
