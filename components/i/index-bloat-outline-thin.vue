<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crv4i00bu"/><path class="wwb_9fbub"/><path class="je5qtm2zh"/><path class="g1xwr4cnp"/><path class="t2ilqxxwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-bloat-outline-thin" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.g1xwr4cnp {
  d: path("M4 14h15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.je5qtm2zh {
  d: path("M4 10h17");
}

.t2ilqxxwv {
  d: path("M4 18h8");
}

.wwb_9fbub {
  d: path("M4 6h12");
}

</style>
