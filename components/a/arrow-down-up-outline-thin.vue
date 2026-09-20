<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gg9qhlhxo"/><path class="v5g-gqbwm"/><path class="pa1ot6bmg"/><path class="wm_1lkfim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-down-up-outline-thin" /></template>
<style>
.gg9qhlhxo {
  d: path("M8 4v16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pa1ot6bmg {
  d: path("M16 4v16");
}

.v5g-gqbwm {
  d: path("m4 16 4 4 4 -4");
}

.wm_1lkfim {
  d: path("m12 8 4 -4 4 4");
}

</style>
