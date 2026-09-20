<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxow7abeb"/><path class="t_uu3mbyc"/><path class="abnm6smsv"/><path class="gk315f5vo"/><path class="tn8-gc8mv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:document-lock-duotone-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.gk315f5vo {
  d: path("M9 12h6v5.5H9Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t_uu3mbyc {
  fill: currentColor;
  d: path("M9 12h6v5.5H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tn8-gc8mv {
  d: path("M10 12a2 2 0 0 1 4 0");
}

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
