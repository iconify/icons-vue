<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eu-8lebac"/><path class="k2xn4nbds"/><path class="gqua-bbkg"/><path class="fo_ekznwu"/><path class="v1ku6ibql"/><path class="ltjpzfbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:layer-up-duotone-thin" /></template>
<style>
.eu-8lebac {
  fill: currentColor;
  d: path("M4 12.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fo_ekznwu {
  d: path("M9.5 4.5 12 2l2.5 2.5");
}

.gqua-bbkg {
  d: path("M12 4v4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2xn4nbds {
  fill: currentColor;
  d: path("M4 19.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ltjpzfbzq {
  d: path("M4 19.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2");
}

.v1ku6ibql {
  d: path("M4 12.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2");
}

</style>
