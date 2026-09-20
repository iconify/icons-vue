<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dzqf6k4yf"/><path class="h2_3d_isv"/><path class="l6vs8g3dv"/><path class="j7f3uspyc"/><path class="rk0ztqbwb"/><path class="ag39tfb0x"/><path class="zy0mbfbon"/><path class="inae6abkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-outbox-duotone-thin" /></template>
<style>
.ag39tfb0x {
  d: path("M12 15v6h10v-6");
}

.dzqf6k4yf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2_3d_isv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 15v6h10v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.inae6abkl {
  d: path("M14.5 10.5 17 8l2.5 2.5");
}

.j7f3uspyc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 10.5 17 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l6vs8g3dv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 8v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rk0ztqbwb {
  d: path("M7.69 3.37a4 4 0 1 1 -3.38 0");
}

.zy0mbfbon {
  d: path("M17 8v5");
}

</style>
