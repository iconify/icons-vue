<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9oa5_bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:exit-interview" /></template>
<style>
.y9oa5_bvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3h4.5A1.75 1.75 0 0 1 11 4.75v15a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 3 19.75v-15A1.75 1.75 0 0 1 4.75 3m3.5 9.25h.01M15.25 4H20a1.5 1.5 0 0 1 1.5 1.5V11a1.5 1.5 0 0 1-1.5 1.5h-3.5L13.75 15V5.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
