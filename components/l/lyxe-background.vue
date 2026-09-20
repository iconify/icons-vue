<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGhGYEodZm)" class="x6td9ac_x"/><path class="yzcarq48i"/><path class="lm3qpibhd"/><path class="d1edribev"/></g><defs><linearGradient id="SVGhGYEodZm" x1="8.886" x2="15.668" y1="5.78" y2="18.081" gradientUnits="userSpaceOnUse"><stop class="bp3j6lb9w"/><stop offset="1" class="u9epcjs3h"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lyxe-background" /></template>
<style>
.bp3j6lb9w {
  stop-color: var(--svg-color--e59f9a, #e59f9a);
}

.d1edribev {
  fill: var(--svg-color--efeeee, #efeeee);
  d: path("m14.038 15.553l-1.995-3.548l1.956-3.561l1.999 3.555z");
}

.ft5dv1b6b {
  fill: none;
}

.lm3qpibhd {
  fill: var(--svg-color--dadbda, #dadbda);
  d: path("M10.05 15.556L8.021 12h4.024l1.994 3.556z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u9epcjs3h {
  stop-color: var(--svg-color--6a3fba, #6a3fba);
}

.x6td9ac_x {
  d: path("m12 4l7.11 3.944v8.111L12 20l-7.111-3.945v-8.11z");
}

.yzcarq48i {
  fill: var(--svg-color--fff, #fff);
  d: path("M14 8.444h-3.978L8 11.999h4.068z");
}

</style>
