<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fce-vbb2c"/><path class="z6s_w0bbl"/><path class="a7h45wbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:deploy-agent-outline-thin" /></template>
<style>
.a7h45wbtv {
  d: path("M15.5 8.5 18 6l2.5 2.5");
}

.fce-vbb2c {
  d: path("M10.11 9.47a5 5 0 1 1 -4.22 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6s_w0bbl {
  d: path("M18 8v11");
}

</style>
