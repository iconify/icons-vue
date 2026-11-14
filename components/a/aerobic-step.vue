<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqk-5lb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aerobic-step" /></template>
<style>
.zqk-5lb_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 8.75l.538-1.211A1.75 1.75 0 0 1 5.637 6.5h12.726a1.75 1.75 0 0 1 1.599 1.039L20.5 8.75A1.6 1.6 0 0 1 19.038 11H4.962A1.6 1.6 0 0 1 3.5 8.75M6.25 11h1.5a1.75 1.75 0 0 1 1.75 1.75v3a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 6.25 11m10 0h1.5a1.75 1.75 0 0 1 1.75 1.75v3a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 16.25 11");
}

</style>
