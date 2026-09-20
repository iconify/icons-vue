<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="e-gm2gt9h"/><path class="g-jss2bnj"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="d2jiu7bqo"/><path class="gzqe0db9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:downsample-duotone-thin" /></template>
<style>
.d2jiu7bqo {
  d: path("m7 15 2 -2 2 2 2 -2");
}

.e-gm2gt9h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 15 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g-jss2bnj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 15 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gzqe0db9p {
  d: path("m15 15 4 -4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
