<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="hii7d4whw"/><path class="wcpvigl8r"/><rect class="z26t-1bol"/><path class="jtax93jnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:city-hall-gov" /></template>
<style>
.hii7d4whw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v2.5M8.75 13V8.5L12 5.25l3.25 3.25V13Z");
}

.jtax93jnm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 15.5v3m12-3v3m-7.25 2.75v-3a1.25 1.25 0 0 1 2.5 0v3");
}

.wcpvigl8r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z26t-1bol {
  width: 18.5px;
  height: 8.25px;
  x: 2.75px;
  y: 13px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

</style>
