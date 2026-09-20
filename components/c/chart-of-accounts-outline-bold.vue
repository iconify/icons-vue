<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y4_6s7b5v"/><path class="wuvisubmw"/><path class="wp75hkmty"/><path class="a2e335b1o"/><path class="u3j9ehbvp"/><path class="aq_yi4bjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-of-accounts-outline-bold" /></template>
<style>
.a2e335b1o {
  d: path("M11 10h5");
}

.aq_yi4bjn {
  d: path("M11 17h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u3j9ehbvp {
  d: path("M11 13.5h5");
}

.wp75hkmty {
  d: path("M11 7v10");
}

.wuvisubmw {
  d: path("M8 3v18");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
