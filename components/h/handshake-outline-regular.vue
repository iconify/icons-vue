<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zuquf0b8s"/><path class="fcstqn4mf"/><path class="f8gsx7b5s"/><path class="qs69rnufu"/><path class="xqfhg19ie"/><path class="q9rcsymqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:handshake-outline-regular" /></template>
<style>
.f8gsx7b5s {
  d: path("M6 8h12");
}

.fcstqn4mf {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q9rcsymqn {
  d: path("m6 16 3 3");
}

.qs69rnufu {
  d: path("m18 8 -3 -3");
}

.xqfhg19ie {
  d: path("M18 16H6");
}

.zuquf0b8s {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
