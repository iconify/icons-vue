<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ae-e09b3w"/><path class="d26wznbgp"/><path class="wm3q5wbwg"/><path class="vblyu6b4h"/><path class="r3snlms8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:air-freight-outline-bold" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.d26wznbgp {
  d: path("M13 12 7 6");
}

.r3snlms8q {
  d: path("m5 12 -2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vblyu6b4h {
  d: path("m5 12 -2 -2");
}

.wm3q5wbwg {
  d: path("m13 12 -6 6");
}

</style>
