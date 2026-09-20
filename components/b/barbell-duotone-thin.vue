<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cc0pq4b_o"/><path class="ydrfk9w6p"/><path class="lg9uabb_p"/><path class="txwhaib5d"/><path class="c8lxf1b3v"/><path class="vslz5yb3q"/><path class="mpjdm200q"/><path class="tkeq0bpvv"/><path class="gfdpeof0d"/><path class="y_uork5-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:barbell-duotone-thin" /></template>
<style>
.c8lxf1b3v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cc0pq4b_o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gfdpeof0d {
  d: path("M9 7v10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lg9uabb_p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mpjdm200q {
  d: path("M6 4v16");
}

.tkeq0bpvv {
  d: path("M18 4v16");
}

.txwhaib5d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vslz5yb3q {
  d: path("M6 12h12");
}

.y_uork5-p {
  d: path("M15 7v10");
}

.ydrfk9w6p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
