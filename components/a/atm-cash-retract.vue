<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nahgk_btt"/><path class="gdisxyp_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atm-cash-retract" /></template>
<style>
.gdisxyp_i {
  d: path("M8.25 13.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nahgk_btt {
  d: path("M4.75 4h14.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25H4.75A2.25 2.25 0 0 1 2.5 6.25A2.25 2.25 0 0 1 4.75 4M4.5 8.5v10q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01h8.672m4.328-7.843V8.5");
}

</style>
