<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="d8ox74zzf"/><circle class="ewe97dbkq"/><circle class="b0w92sb7y"/><circle class="p-5p0ybdn"/><circle class="c1ojufzoa"/><circle class="j1g30gqap"/><circle class="pa5iz9cvw"/><path class="de20-lboz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:big-dipper" /></template>
<style>
.b0w92sb7y {
  cx: 11.25px;
  cy: 9.25px;
  r: 1.25px;
}

.c1ojufzoa {
  cx: 13.75px;
  cy: 18.75px;
  r: 1.25px;
}

.d8ox74zzf {
  cx: 4.25px;
  cy: 5px;
  r: 1.25px;
}

.de20-lboz {
  d: path("m6.42 6.01l-.59-.27M9.9 8.21l-.55-.42m3.09 3.54l-.38-.66m1.39 4.47l.1 1.22m2.6 2.49l1.2.05m2.4-2.3v-1.45m-2.4-2.4h-1.7");
}

.ewe97dbkq {
  cx: 8px;
  cy: 6.75px;
  r: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j1g30gqap {
  cx: 19.75px;
  cy: 19px;
  r: 1.25px;
}

.p-5p0ybdn {
  cx: 13.25px;
  cy: 12.75px;
  r: 1.25px;
}

.pa5iz9cvw {
  cx: 19.75px;
  cy: 12.75px;
  r: 1.25px;
}

</style>
