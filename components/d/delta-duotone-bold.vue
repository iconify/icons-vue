<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z30u_6b6k"/><path class="d6o_ccoql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:delta-duotone-bold" /></template>
<style>
.d6o_ccoql {
  d: path("m3 17 9 -9 9 9Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z30u_6b6k {
  fill: currentColor;
  d: path("m3 17 9 -9 9 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
