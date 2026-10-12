<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bz8-jxbeo"/><path class="hpoh1mqlt"/><path class="vr-spacyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:derma-roller-sharp" /></template>
<style>
.bz8-jxbeo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75h12.5v5.5H5.75z");
}

.hpoh1mqlt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 4.5h.01m3.24 0h.01m3.24 0h.01m-4.86 2h.01m3.19 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vr-spacyn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 5.5v5h17.5v-5m-8.75 5v2.25m-1.75 0h3.5v8.5h-3.5z");
}

</style>
