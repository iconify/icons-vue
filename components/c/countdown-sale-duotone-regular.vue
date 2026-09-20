<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cuso263ot"/><path class="ezik40n3m"/><path class="mby676_xn"/><path class="a5kh06x1k"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/><path class="b266jkbmh"/><path class="m-436sbse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:countdown-sale-duotone-regular" /></template>
<style>
.a5kh06x1k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 21v-4l5 -5 5 5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b266jkbmh {
  d: path("M7 3v4l5 5 5 -5V3");
}

.cuso263ot {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 3h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ezik40n3m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m-436sbse {
  d: path("M7 21v-4l5 -5 5 5v4");
}

.mby676_xn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3v4l5 5 5 -5V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rjrs_5bsc {
  d: path("M6 3h12");
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>
