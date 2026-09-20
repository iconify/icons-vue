<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jiieap29k"/><path class="oegd6zb7w"/><path class="bi4el8ygv"/><path class="zqoml3bvy"/><path class="oe2rn1bbo"/><path class="gtsw5xviq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:leash-short-duotone-thin" /></template>
<style>
.bi4el8ygv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gtsw5xviq {
  d: path("M17 5v14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jiieap29k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.11 7.47a5 5 0 1 1 -4.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oe2rn1bbo {
  d: path("M14 12h3");
}

.oegd6zb7w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zqoml3bvy {
  d: path("M11.11 7.47a5 5 0 1 1 -4.22 0");
}

</style>
