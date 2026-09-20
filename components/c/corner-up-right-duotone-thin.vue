<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tknbn6b9k"/><path class="b8yamqbxk"/><path class="uhkbmlahb"/><path class="vmh-l_baq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-up-right-duotone-thin" /></template>
<style>
.b8yamqbxk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 5 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tknbn6b9k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20V10h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uhkbmlahb {
  d: path("M4 20V10h16");
}

.vmh-l_baq {
  d: path("m15 5 5 5 -5 5");
}

</style>
