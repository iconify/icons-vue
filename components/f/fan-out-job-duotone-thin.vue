<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vws5wpblq"/><path class="cn7hoepxw"/><path class="sznyy028z"/><path class="ri2m-q_tv"/><path class="f0erpifmh"/><path class="gscgthrgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fan-out-job-duotone-thin" /></template>
<style>
.cn7hoepxw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12h3l3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f0erpifmh {
  d: path("M7 12h3l3 -3h3");
}

.gscgthrgv {
  d: path("m10 12 3 3h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.sznyy028z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 12 3 3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vws5wpblq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
