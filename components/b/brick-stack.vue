<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="q1jojibiu"/><rect class="cm5asn7kn"/><rect class="t9_gncbkp"/><path class="du4790boy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brick-stack" /></template>
<style>
.cm5asn7kn {
  width: 7.75px;
  height: 7px;
  x: 13.5px;
  y: 14.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.du4790boy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 17.75h.01m2.74 0h.01m7.99 0h.01m2.74 0h.01m-8.26-10h.01m2.99 0h.01");
}

.q1jojibiu {
  width: 7.75px;
  height: 7px;
  x: 2.75px;
  y: 14.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.t9_gncbkp {
  width: 8.5px;
  height: 7px;
  x: 7.75px;
  y: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
