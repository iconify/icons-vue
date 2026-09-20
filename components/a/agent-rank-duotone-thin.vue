<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h1x261med"/><path class="u5anhrb_i"/><path class="t1ypwibon"/><path class="ps-_1ne9q"/><path class="s_yfbmb1g"/><path class="krpni0u_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-rank-duotone-thin" /></template>
<style>
.h1x261med {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 3.33a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krpni0u_o {
  d: path("m7 22 5 -5 5 5");
}

.ps-_1ne9q {
  d: path("M13.5 3.33a3.5 3.5 0 1 1 -2.96 0");
}

.s_yfbmb1g {
  d: path("m7 17.5 5 -5 5 5");
}

.t1ypwibon {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 22 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u5anhrb_i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 17.5 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
