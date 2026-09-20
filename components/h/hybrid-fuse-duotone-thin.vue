<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k0tt36b3y"/><path class="r9nv4mbii"/><path class="jb3sa9bbh"/><path class="tnqcnjluk"/><path class="pr6npvbsh"/><path class="xxvssxb6x"/><path class="lqiw_3bos"/><path class="dhtq24lfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hybrid-fuse-duotone-thin" /></template>
<style>
.dhtq24lfs {
  d: path("m17 9.5 2.5 2.5 -2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jb3sa9bbh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k0tt36b3y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 5 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lqiw_3bos {
  d: path("M10 12h7");
}

.pr6npvbsh {
  d: path("m3 5 6 6");
}

.r9nv4mbii {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 19 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tnqcnjluk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 9.5 2.5 2.5 -2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xxvssxb6x {
  d: path("m3 19 6 -6");
}

</style>
