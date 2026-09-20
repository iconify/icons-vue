<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ieygsmq-l"/><path class="c0qupkqan"/><path class="a_mnj8b4u"/><path class="at5b1xbsc"/><path class="xtf0w138e"/><path class="a5tuk3h7e"/><path class="scwel3iok"/><path class="akar2ebka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drum-duotone-regular" /></template>
<style>
.a_mnj8b4u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 8 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.a5tuk3h7e {
  d: path("M4 10h16");
}

.akar2ebka {
  d: path("m18 8 -4 -4");
}

.at5b1xbsc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 8 -4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c0qupkqan {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ieygsmq-l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10v7h16v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.scwel3iok {
  d: path("m6 8 4 -4");
}

.xtf0w138e {
  d: path("M4 10v7h16v-7");
}

</style>
