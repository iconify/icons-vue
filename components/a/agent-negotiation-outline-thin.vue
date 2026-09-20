<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h7k_twb0c"/><path class="x1wxn1ypz"/><path class="wm0jgrm5t"/><path class="wy-6ptr_q"/><path class="oi40jf9zq"/><path class="xb0ugqbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-negotiation-outline-thin" /></template>
<style>
.h7k_twb0c {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oi40jf9zq {
  d: path("M7.5 15v-2.5H10");
}

.wm0jgrm5t {
  d: path("M16.5 9v2.5H14");
}

.wy-6ptr_q {
  d: path("m11 16 -3 -3");
}

.x1wxn1ypz {
  d: path("m13 8 3 3");
}

.xb0ugqbkt {
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
}

</style>
