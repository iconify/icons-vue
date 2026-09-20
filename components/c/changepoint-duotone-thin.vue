<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="toso_pb8v"/><path class="w00q2fbhs"/><path class="loqr5yt1s"/><path class="g-wxd1xvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:changepoint-duotone-thin" /></template>
<style>
.g-wxd1xvy {
  d: path("M12 5v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.loqr5yt1s {
  d: path("M4 10h8l7 7");
}

.toso_pb8v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 10h8l7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w00q2fbhs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
