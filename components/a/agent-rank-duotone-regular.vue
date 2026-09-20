<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i5la5ub6n"/><path class="f0ob5_p5e"/><path class="krhtk3n3j"/><path class="ps-_1ne9q"/><path class="s_yfbmb1g"/><path class="krpni0u_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-rank-duotone-regular" /></template>
<style>
.f0ob5_p5e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 17.5 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i5la5ub6n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 3.33a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.krhtk3n3j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 22 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.krpni0u_o {
  d: path("m7 22 5 -5 5 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ps-_1ne9q {
  d: path("M13.5 3.33a3.5 3.5 0 1 1 -2.96 0");
}

.s_yfbmb1g {
  d: path("m7 17.5 5 -5 5 5");
}

</style>
