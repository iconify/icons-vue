<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="jq_c3bc4g"/><path class="izqnth1lx"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="q8d90--8n"/><path class="bfi7-obrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:http-get-duotone-thin" /></template>
<style>
.bfi7-obrv {
  d: path("M9.5 11.5 12 14l2.5 -2.5");
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.eh---ab1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.izqnth1lx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 11.5 12 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jq_c3bc4g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8.5V14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.q8d90--8n {
  d: path("M12 8.5V14");
}

.r1p5_ebae {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
