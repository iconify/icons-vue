<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lyyswacbl"/><path class="uxsptjbvt"/><path class="opa9u3lld"/><path class="iqbnu2-gg"/><path class="wcrnibsiv"/><path class="w16x_q5cd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:certificate-expiry-outline-bold" /></template>
<style>
.iqbnu2-gg {
  d: path("M11.5 18a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.lyyswacbl {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.opa9u3lld {
  d: path("M6 11h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uxsptjbvt {
  d: path("M6 7h12");
}

.w16x_q5cd {
  d: path("M15 18h2.5");
}

.wcrnibsiv {
  d: path("M15 15.5V18");
}

</style>
