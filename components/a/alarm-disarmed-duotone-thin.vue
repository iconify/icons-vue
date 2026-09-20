<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u96j_1b8m"/><path class="c2nlsybqj"/><path class="zshu2cj5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:alarm-disarmed-duotone-thin" /></template>
<style>
.c2nlsybqj {
  d: path("M12 3s4 2 8 3v6c0 5 -4 8 -8 9 -4 -1 -8 -4 -8 -9V6c4 -1 8 -3 8 -3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u96j_1b8m {
  fill: currentColor;
  d: path("M12 3s4 2 8 3v6c0 5 -4 8 -8 9 -4 -1 -8 -4 -8 -9V6c4 -1 8 -3 8 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zshu2cj5h {
  d: path("m8 15 8 -8");
}

</style>
