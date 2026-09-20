<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="opz6_8zup"/><path class="wdl213b6n"/><path class="cfd43lbgp"/><path class="yhnjhi90f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:baby-bottle-duotone-thin" /></template>
<style>
.cfd43lbgp {
  d: path("M7 13h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.opz6_8zup {
  fill: currentColor;
  d: path("M7 21V9h10v12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wdl213b6n {
  d: path("M7 21V9h10v12Z");
}

.yhnjhi90f {
  d: path("M10 9V6.5a2 2 0 0 1 4 0V9");
}

</style>
