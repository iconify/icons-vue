<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxow7abeb"/><path class="q-if2acds"/><path class="abnm6smsv"/><path class="vargix3eq"/><path class="yh_ipqbbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:document-clock-duotone-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.q-if2acds {
  fill: currentColor;
  d: path("M8.5 12.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vargix3eq {
  d: path("M8.5 12.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.yh_ipqbbf {
  d: path("M12 9.5v3h2.5");
}

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
