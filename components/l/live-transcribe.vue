<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f7la76n6z"/><path class="im2hqabsd"/><path class="hqpru_big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:live-transcribe" /></template>
<style>
.f7la76n6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.755 34.842H8.167a2.795 2.795 0 0 1-2.794-2.795V8.294A2.794 2.794 0 0 1 8.167 5.5h14.364Z");
}

.hqpru_big {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.402 21.105a6.765 6.765 0 0 0 13.285 0m-6.643 5.484v3.336m11.925-8.82h11.25m-7.835 9.799h7.835m-9.488-4.899h9.488");
}

.im2hqabsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.2 13.159h14.633a2.795 2.795 0 0 1 2.794 2.794v23.753a2.794 2.794 0 0 1-2.794 2.794H25.469L22.8 34.841m9.955.001L25.469 42.5m-9.425-31.43za3.96 3.96 0 0 1 3.96 3.96v4.896a3.96 3.96 0 0 1-3.96 3.96a3.96 3.96 0 0 1-3.96-3.96v-4.895a3.96 3.96 0 0 1 3.96-3.96");
}

</style>
