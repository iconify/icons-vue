<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hwufvfb8q"/><path class="wlp3ibbib"/><path class="lg-3ttj_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:garage-outline-bold" /></template>
<style>
.hwufvfb8q {
  d: path("M3 20v-8l9 -9 9 9v8Z");
}

.lg-3ttj_m {
  d: path("M6 16.5h12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wlp3ibbib {
  d: path("M6 13h12");
}

</style>
