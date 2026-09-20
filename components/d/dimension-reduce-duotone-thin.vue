<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nucukxqhx"/><path class="f6oss7nrv"/><path class="sfyvujw3a"/><path class="yg83_ebrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dimension-reduce-duotone-thin" /></template>
<style>
.f6oss7nrv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18.5 14 2.5 2.5 -4 4 -4 -4 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nucukxqhx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 4 4 4 -6.5 6.5L4 8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sfyvujw3a {
  d: path("m13 4 4 4 -6.5 6.5L4 8l4 -4");
}

.yg83_ebrk {
  d: path("m18.5 14 2.5 2.5 -4 4 -4 -4 2.5 -2.5");
}

</style>
