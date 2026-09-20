<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k-xzyt36j"/><path class="uzkjx1-8e"/><path class="hdoh9g9pr"/><path class="evcx__bzi"/><path class="l2nbo7bgf"/><path class="l8dn9jbyp"/><path class="tla8vyn6c"/><path class="olqfcgidt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:half-board-duotone-thin" /></template>
<style>
.evcx__bzi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hdoh9g9pr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-xzyt36j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 15a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l2nbo7bgf {
  d: path("M4 15a8 8 0 0 1 16 0");
}

.l8dn9jbyp {
  d: path("M2 15h20");
}

.olqfcgidt {
  d: path("M6 19h12");
}

.tla8vyn6c {
  d: path("M12 7v8");
}

.uzkjx1-8e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
