<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="plajqrbag"/><path class="l9e2wtb8u"/><path class="zw9mi34de"/><path class="aex4p0z2m"/><path class="ktyyc-bmz"/><path class="ajwjssc6m"/><path class="timme522h"/><path class="idl7fxbhb"/><path class="vzfmp7bra"/><path class="ipwz79qoh"/><path class="j3lsn4bia"/><path class="dc0xg9bgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dust-storm-duotone-thin" /></template>
<style>
.aex4p0z2m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ajwjssc6m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dc0xg9bgf {
  d: path("M9 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.idl7fxbhb {
  d: path("m17 6 3 -3");
}

.ipwz79qoh {
  d: path("m19 11 3 -3");
}

.j3lsn4bia {
  d: path("M3 16h12");
}

.ktyyc-bmz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19 11 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l9e2wtb8u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plajqrbag {
  fill: currentColor;
  d: path("M9 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.timme522h {
  d: path("M3 6h14");
}

.vzfmp7bra {
  d: path("M5 11h14");
}

.zw9mi34de {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 6 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
