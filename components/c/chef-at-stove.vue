<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4rlngodi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chef-at-stove" /></template>
<style>
.h4rlngodi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h19M4 10v8q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036t.245.012h6.473M20 11.054V10M9.5 7.25c-1-1.5 1-2.75 0-4.25m5 4.25c-1-1.5 1-2.75 0-4.25m1.75 18.5h3.5v-2.25a1.75 1.75 0 0 0 1-3a2.75 2.75 0 0 0-5.5 0a1.75 1.75 0 0 0 1 3Z");
}

</style>
