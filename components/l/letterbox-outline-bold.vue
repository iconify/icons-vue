<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ra07l749q"/><path class="zawirs49s"/><path class="itq_ntb3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:letterbox-outline-bold" /></template>
<style>
.itq_ntb3g {
  d: path("M11 16v5");
}

.ra07l749q {
  d: path("M5 16v-6a6 6 0 0 1 12 0v6Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zawirs49s {
  d: path("M8 11h6");
}

</style>
