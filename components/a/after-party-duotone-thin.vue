<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pzmvcyk0g"/><path class="f745tra4m"/><path class="ypr8o0dzv"/><path class="a2jmonbvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:after-party-duotone-thin" /></template>
<style>
.a2jmonbvk {
  d: path("M6 14h14l-7 7Z");
}

.f745tra4m {
  fill: currentColor;
  d: path("M6 14h14l-7 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pzmvcyk0g {
  fill: currentColor;
  d: path("M7 3C5 4.5 4 7 5 9s3 2.5 4.5 2c-1 -1.5 -1.5 -3.5 -1 -5.5 0.3 -1 -0.5 -2 -1.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ypr8o0dzv {
  d: path("M7 3C5 4.5 4 7 5 9s3 2.5 4.5 2c-1 -1.5 -1.5 -3.5 -1 -5.5 0.3 -1 -0.5 -2 -1.5 -2.5");
}

</style>
