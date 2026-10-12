<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="b9g-8nbgz"/><path class="p5rad8bcm"/><path class="cs185qb-c"/><path class="ozi5zcc5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lock-keyhole-round" /></template>
<style>
.b9g-8nbgz {
  cx: 12px;
  cy: 15px;
  r: 6.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.cs185qb-c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14h.01");
}

.ozi5zcc5p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14.75v2.5");
}

.p5rad8bcm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10.5V7a4 4 0 0 1 8 0v3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
