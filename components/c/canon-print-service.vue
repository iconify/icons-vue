<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ynbjozw5d"/><path class="ovsl86llo"/><ellipse class="ya3f8nbeo"/><path class="wychau0zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:canon-print-service" /></template>
<style>
.ovsl86llo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.418 11.48h-8.836l-.982 3.3h10.8zM11.292 24.287l25.172-.057l2.683 13.527H8.853zm3.337 2.731l-.09 7.61m4.851-6.504l.002 5.043m2.72 1.729l13.935.028");
}

.wychau0zn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.621 29.505l5.114-.307l1.97-2.343m-1.679 2.238l1.448 2.871m-20.527-6.606H9.5l.026-3.81H38.14l.052 3.81h-1.147");
}

.ya3f8nbeo {
  cx: 29.717px;
  cy: 29.401px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.138px;
  ry: 2.869px;
}

.ynbjozw5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 18.782h37v21.74h-37zM38.18 7.478H9.82L5.5 18.782h37z");
}

</style>
