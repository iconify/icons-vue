<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="znp-i32pq"/><path class="mcihf2b2e"/><path class="cigo6d7sj"/><path class="isignkb_m"/><path class="h7k_twb0c"/><path class="crfmflbxb"/><path class="ih1xqsb_s"/><path class="xb0ugqbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-delegate-duotone-regular" /></template>
<style>
.cigo6d7sj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11.5 14H14v-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.crfmflbxb {
  d: path("m10 10 2.5 2.5");
}

.h7k_twb0c {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

.ih1xqsb_s {
  d: path("M11.5 14H14v-2.5");
}

.isignkb_m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcihf2b2e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 10 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xb0ugqbkt {
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
}

.znp-i32pq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
