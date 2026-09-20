<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e7pgrp-wx"/><path class="hcqml3bhu"/><path class="p2i6q-ifg"/><path class="ldxs-ebdf"/><path class="dt_d4knyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:load-balancer-outline-regular" /></template>
<style>
.dt_d4knyh {
  d: path("M8 18h13");
}

.e7pgrp-wx {
  d: path("M2 12h6");
}

.hcqml3bhu {
  d: path("M8 6v12");
}

.ldxs-ebdf {
  d: path("M8 12h13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p2i6q-ifg {
  d: path("M8 6h13");
}

</style>
