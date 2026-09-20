<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v2mnclz8q"/><path class="or5zzfb5w"/><path class="moq23nqoi"/><path class="ovlj_c6ad"/><path class="n_sq8uh7x"/><path class="d_b1a31kv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:horse-riding-duotone-thin" /></template>
<style>
.d_b1a31kv {
  d: path("M10 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.moq23nqoi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n_sq8uh7x {
  d: path("M8 12h9");
}

.or5zzfb5w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 21v-8c0 -4 3 -7 7 -7h2.5l3 -3v5c2 2 2.5 4 2.5 7v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ovlj_c6ad {
  d: path("M5 21v-8c0 -4 3 -7 7 -7h2.5l3 -3v5c2 2 2.5 4 2.5 7v6");
}

.v2mnclz8q {
  fill: currentColor;
  d: path("M10 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
