<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c-pcdbceg"/><path class="ykv448byy"/><path class="z6i5xtbsj"/><path class="l2z94vbar"/><path class="qvk3j9bfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:heavy-rain-outline-regular" /></template>
<style>
.c-pcdbceg {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

.l2z94vbar {
  d: path("m14 15.5 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qvk3j9bfo {
  d: path("m18 18 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

.ykv448byy {
  d: path("M6 15.5 8.5 18a2.5 2.5 0 0 1 -5 0Z");
}

.z6i5xtbsj {
  d: path("m10 18 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

</style>
