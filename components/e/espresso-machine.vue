<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="gi9q0-bpw"/><path class="mkzk6zbbr"/><path class="ns5fyom1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:espresso-machine" /></template>
<style>
.gi9q0-bpw {
  width: 17.5px;
  height: 6.5px;
  x: 3.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.mkzk6zbbr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 6h.01");
}

.ns5fyom1j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 6h4.25m-8.5 3.25v2.5h7.5v-2.5m-11.5 0v12m15.5-12v12m-17 0h18.5M9 15h6v4.25a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
