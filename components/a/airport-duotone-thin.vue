<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="etg-cfc2o"/><path class="m211msb-t"/><path class="ymhw07_9a"/><path class="yomj0bbqc"/><path class="ay19-ob6x"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:airport-duotone-thin" /></template>
<style>
.ay19-ob6x {
  d: path("m6 9 4.5 -4.5h3L18 9");
}

.bos0j4biy {
  d: path("M3 21h18");
}

.etg-cfc2o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 21V9h6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m211msb-t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 9 4.5 -4.5h3L18 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ymhw07_9a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yomj0bbqc {
  d: path("M9 21V9h6v12");
}

</style>
