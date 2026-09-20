<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gj9my0bph"/><path class="xgx-opjvu"/><path class="ext7qtobs"/><path class="ia95t8sod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:escalation-duotone-bold" /></template>
<style>
.ext7qtobs {
  d: path("M3 19h5v-5h5V9h6");
}

.gj9my0bph {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h5v-5h5V9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ia95t8sod {
  d: path("m16 6 3 3 -3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xgx-opjvu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 6 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
