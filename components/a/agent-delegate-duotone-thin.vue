<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ycktj7b1l"/><path class="r58-3mbfe"/><path class="mosx_7efl"/><path class="wu-aokb4s"/><path class="h7k_twb0c"/><path class="crfmflbxb"/><path class="ih1xqsb_s"/><path class="xb0ugqbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-delegate-duotone-thin" /></template>
<style>
.crfmflbxb {
  d: path("m10 10 2.5 2.5");
}

.h7k_twb0c {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ih1xqsb_s {
  d: path("M11.5 14H14v-2.5");
}

.mosx_7efl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.5 14H14v-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r58-3mbfe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 10 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wu-aokb4s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xb0ugqbkt {
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
}

.ycktj7b1l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
