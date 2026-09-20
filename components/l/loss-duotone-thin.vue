<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vpuel0dtu"/><path class="r9hag8bpw"/><path class="q823z0z0d"/><path class="crv4i00bu"/><path class="wy8w_b5cr"/><path class="nzwwf5-_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:loss-duotone-thin" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzwwf5-_s {
  d: path("m6 5 6 6 3 3h5");
}

.q823z0z0d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 5 6 6 3 3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r9hag8bpw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vpuel0dtu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wy8w_b5cr {
  d: path("M4 21h18");
}

</style>
