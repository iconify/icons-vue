<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gl_c0p6sd"/><path class="z42xzcoix"/><path class="dxqp15kpa"/><path class="klyrig6if"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-step-duotone-thin" /></template>
<style>
.dxqp15kpa {
  d: path("M8.69 8.37a4 4 0 1 1 -3.38 0");
}

.gl_c0p6sd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.klyrig6if {
  d: path("m14 7 5 5 -5 5");
}

.z42xzcoix {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
