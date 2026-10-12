<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vmp6-t5jj"/><rect class="s79jc_45c"/><path class="t2jubdc-i"/><path class="rxo43kb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:controller-retro" /></template>
<style>
.rxo43kb9y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 13h.01m2.99-2h.01");
}

.s79jc_45c {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 7.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.t2jubdc-i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12.5H9m-1.75-1.75v3.5m3.5-.25h2.5");
}

.vmp6-t5jj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5V5.25a2.5 2.5 0 0 1 2.5-2.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
