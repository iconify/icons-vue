<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii3zeqysd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:c-section" /></template>
<style>
.ii3zeqysd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5C6.5 6 6 9 5.5 12s0 6.5 1 9.5m3.5-19c.5 2 .5 3.5 0 5c3.5.5 8 2.5 9.5 6c1.25 3-.5 6-3.5 7.25q-2.25.75-4.5.75m0-3.5H17m-4-1.25v2.5m2.5-2.5v2.5");
}

</style>
