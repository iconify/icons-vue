<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rte53dt0e"/><path class="vgg01abra"/><path class="t2b-y0b8a"/><path class="dv1ipeb_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-minimum-balance" /></template>
<style>
.dv1ipeb_u {
  d: path("M6 14.5v.75a6.75 3.25 0 0 0 13.5 0V12.5m-6.75-6.25c-.09-.36-.37-.49-.75-.5c-.46.01-.74.24-.75.5c.01.78 1.49.49 1.5 1.5c-.01.24-.32.49-.75.5c-.4-.01-.68-.18-.75-.5m.75-3v.75m0 3v.75m-9.5 12h2m3 0h3m3 0h3m3 0h2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rte53dt0e {
  d: path("M5.25 7a6.75 3.25 0 1 0 13.5 0a6.75 3.25 0 1 0-13.5 0");
}

.t2b-y0b8a {
  d: path("M4.5 9.75v2.75a6.75 3.25 0 0 0 13.5 0v-1.25");
}

.vgg01abra {
  d: path("M5.25 7v2.75a6.75 3.25 0 0 0 13.5 0V7");
}

</style>
