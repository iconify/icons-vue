<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i_8-ulbnm"/><path class="d0ca424zn"/><path class="s91v-jwfo"/><path class="j2vmgobzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ambulance-van-sharp" /></template>
<style>
.d0ca424zn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 11.25h16.5m-14 0L7 8.5h10l.75 2.75m-5.75 2v3.5M10.25 15h3.5");
}

.i_8-ulbnm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3h5.5m-11 3h16.5v13H3.75z");
}

.j2vmgobzr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 19v2m11-2v2");
}

.s91v-jwfo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 15h.01m10.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
