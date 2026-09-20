<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rait5obsl"/><path class="wj6ylmbne"/><path class="i-2dnzb7m"/><path class="qw7b_6b1t"/><path class="z9owi-ayh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cocktail-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-2dnzb7m {
  d: path("M12 14v6");
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.rait5obsl {
  fill: currentColor;
  d: path("M4 6h16l-8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wj6ylmbne {
  d: path("M4 6h16l-8 8Z");
}

.z9owi-ayh {
  d: path("m15 8 4 -4");
}

</style>
