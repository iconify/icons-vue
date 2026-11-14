<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsvvo95fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anvil" /></template>
<style>
.nsvvo95fm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5h19v3H19c-2 0-3.25 1.5-3.25 3.5v4m-7.5 0v-4c0-3-2.75-4-5.75-6.5M6.75 15h10.5A1.75 1.75 0 0 1 19 16.75v1a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 17.75v-1A1.75 1.75 0 0 1 6.75 15");
}

</style>
