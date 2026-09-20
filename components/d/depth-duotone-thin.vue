<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocy7tqb7w"/><path class="enze833yy"/><path class="spyeseu2o"/><path class="naxvjtbgo"/><path class="csk4szidm"/><path class="efg_y9-xm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:depth-duotone-thin" /></template>
<style>
.csk4szidm {
  d: path("M3 11a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

.efg_y9-xm {
  d: path("M3 18a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

.enze833yy {
  fill: currentColor;
  d: path("M3 11a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
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

.naxvjtbgo {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

.ocy7tqb7w {
  fill: currentColor;
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.spyeseu2o {
  fill: currentColor;
  d: path("M3 18a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
