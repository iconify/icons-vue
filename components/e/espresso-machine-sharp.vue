<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wkhkbbopp"/><path class="mkzk6zbbr"/><path class="a0kuyobww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:espresso-machine-sharp" /></template>
<style>
.a0kuyobww {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 6h4.25m-8.5 3.25v2.5h7.5v-2.5m-11.5 0v12m15.5-12v12m-17 0h18.5M9 15h6v6.25H9v-2Z");
}

.mkzk6zbbr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 6h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wkhkbbopp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 2.75h17.5v6.5H3.25z");
}

</style>
