<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s_fg2fb6v"/><path class="mlq5dybnn"/><path class="pq65d4pux"/><path class="wuavqcbqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-up-left-duotone-bold" /></template>
<style>
.mlq5dybnn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 5 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pq65d4pux {
  d: path("M20 20V10H4");
}

.s_fg2fb6v {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 20V10H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wuavqcbqp {
  d: path("m9 5 -5 5 5 5");
}

</style>
