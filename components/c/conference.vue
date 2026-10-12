<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h-72_8bhr"/><path class="oha_9zklb"/><circle class="u_urt4jrw"/><circle class="fggvvekwy"/><circle class="aeekdrycf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:conference" /></template>
<style>
.aeekdrycf {
  cx: 18.5px;
  cy: 18px;
  r: 2px;
}

.fggvvekwy {
  cx: 12px;
  cy: 18px;
  r: 2px;
}

.h-72_8bhr {
  width: 16.5px;
  height: 10px;
  x: 3.75px;
  y: 2.75px;
  rx: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oha_9zklb {
  d: path("M7.75 7.75h8.5");
}

.u_urt4jrw {
  cx: 5.5px;
  cy: 18px;
  r: 2px;
}

</style>
