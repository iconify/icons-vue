<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ixb4-dkjv"/><path class="fy8i8zb3k"/><path class="p-feiispo"/><path class="m3worbckk"/><path class="cqnexabvb"/><path class="ea3ekee5h"/><path class="o-lyxcngp"/><path class="s6wepcb6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compensate-duotone-thin" /></template>
<style>
.cqnexabvb {
  d: path("M4 8h13");
}

.ea3ekee5h {
  d: path("M17 5.5 19.5 8 17 10.5");
}

.fy8i8zb3k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 5.5 19.5 8 17 10.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixb4-dkjv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m3worbckk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 13.5 4.5 16 7 18.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o-lyxcngp {
  d: path("M7 16h13");
}

.p-feiispo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 16h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s6wepcb6n {
  d: path("M7 13.5 4.5 16 7 18.5");
}

</style>
