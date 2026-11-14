<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r55i1s2sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mad-science" /></template>
<style>
.r55i1s2sp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 10.5V13L4 21.5h16L14.5 13v-2.5m-4.5-4a2 2 0 1 0 4 0a2 2 0 1 0-4 0M15.5 3h.01M8 3.5h.01m-.76 13h9.5");
}

</style>
