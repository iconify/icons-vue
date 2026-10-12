<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="klr8e34je"/><path class="fjrh6hbce"/><path class="np225_bxb"/><path class="h365r_ndt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gorilla-sharp" /></template>
<style>
.fjrh6hbce {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 10.75V9.5h7v2l-.5.5l1 1v1.5c0 1.75-1.5 3-3.75 3s-4-1.25-4-3V13l1-1l-.75-.375z");
}

.h365r_ndt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 15h2");
}

.klr8e34je {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25c4.5 0 7.5 3.25 7.5 7.75v3c0 4-3.25 6.75-7.5 6.75S4.5 18 4.5 14v-3c0-4.5 3-7.75 7.5-7.75Z");
}

.np225_bxb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 12h.01m2.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
