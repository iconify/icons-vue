<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l48yz708p"/><path class="uweslxo3x"/><path class="o5dmv_b0u"/><path class="j7s0b5bvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ice-warning-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7s0b5bvf {
  d: path("M15 13.5v5m-2.5 0 5 -5");
}

.l48yz708p {
  fill: currentColor;
  d: path("M12 3.5 21.5 20h-19Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o5dmv_b0u {
  d: path("M9 11.5v5m-2.5 0 5 -5");
}

.uweslxo3x {
  d: path("M12 3.5 21.5 20h-19Z");
}

</style>
