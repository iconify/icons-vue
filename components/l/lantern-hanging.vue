<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quwu3-bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lantern-hanging" /></template>
<style>
.quwu3-bnp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h12m-6 0v3m.937.75l3.5 2.8A1.5 1.5 0 0 1 17 10.221v6.849a1.5 1.5 0 0 1-.228.795l-1.831 2.93a1.5 1.5 0 0 1-1.272.705h-3.338a1.5 1.5 0 0 1-1.272-.705l-1.831-2.93A1.5 1.5 0 0 1 7 17.07v-6.849a1.5 1.5 0 0 1 .563-1.171l3.5-2.8a1.5 1.5 0 0 1 1.874 0M7 9.5h10m-7 2.75V18m4-5.75V18");
}

</style>
