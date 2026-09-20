<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="skbifdbcx"/><path class="f2m4wubik"/><path class="zl61012kd"/><path class="u4kp6lp9x"/><path class="qyl16slsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-sync-outline-regular" /></template>
<style>
.f2m4wubik {
  d: path("M13 12h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qyl16slsb {
  d: path("M17.5 16.5 15 19l2.5 2.5");
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.u4kp6lp9x {
  d: path("M15 19h6");
}

.zl61012kd {
  d: path("M18.5 9.5 21 12l-2.5 2.5");
}

</style>
