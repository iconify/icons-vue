<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="km9uii_ku"/><path class="pd-e3b50j"/><path class="fj0-w8bxo"/><path class="ri2m-q_tv"/><path class="ho-f2ccpq"/><path class="oywe9jbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fan-in-job-duotone-bold" /></template>
<style>
.fj0-w8bxo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 15h3l3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ho-f2ccpq {
  d: path("M8 9h3l3 3h3");
}

.km9uii_ku {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oywe9jbcq {
  d: path("M8 15h3l3 -3");
}

.pd-e3b50j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 9h3l3 3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
