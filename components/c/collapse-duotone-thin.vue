<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iyz5wnvvj"/><path class="decq7rnwt"/><path class="gxit94ujw"/><path class="z-ujbjwsw"/><path class="z_leajngu"/><path class="ptvhb3bfe"/><path class="b8xluzc6p"/><path class="v6f1oidhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:collapse-duotone-thin" /></template>
<style>
.b8xluzc6p {
  d: path("M14 20v-6h6");
}

.decq7rnwt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 10 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gxit94ujw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 20v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iyz5wnvvj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 4v6H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ptvhb3bfe {
  d: path("M10 10 4 4");
}

.v6f1oidhi {
  d: path("m14 14 6 6");
}

.z_leajngu {
  d: path("M10 4v6H4");
}

.z-ujbjwsw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 14 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
