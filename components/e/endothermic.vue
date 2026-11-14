<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l47z86b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:endothermic" /></template>
<style>
.l47z86b2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3L4 4.5v14q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036T6.5 21H12q.211 0 .418-.035q.208-.035.407-.105t.383-.171q.184-.102.349-.233m.943-4.881V3M9.25 8.5v6M6.75 10l5 3m-5 0l5-3M18 14.5V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
