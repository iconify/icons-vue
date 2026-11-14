<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lbdvc5t_e"/><path class="tijhko24y"/><path class="dq8pa_bnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-car-mount" /></template>
<style>
.dq8pa_bnw {
  d: path("M17 19.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.lbdvc5t_e {
  d: path("M2.5 11V8.5A1.5 1.5 0 0 1 4 7h1l2.5-3.5H13L15.75 7H18a1.5 1.5 0 0 1 1.5 1.5V11Z");
}

.tijhko24y {
  d: path("M4.75 12.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm8 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm2.25 5.5a1 1 0 0 1 1-1h.75l.75-1H19l.75 1h.75a1 1 0 0 1 1 1v2.5a1 1 0 0 1-1 1H16a1 1 0 0 1-1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
