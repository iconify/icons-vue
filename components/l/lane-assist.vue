<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7uivuhyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lane-assist" /></template>
<style>
.u7uivuhyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 2.75l-4.25 18.5M17 2.75l4.25 18.5M7.75 17v-1.75q0-1.25.42-2.43l.66-1.89q.42-1.18 1.67-1.18h3q1.25 0 1.67 1.18l.66 1.89q.42 1.18.42 2.43V17q0 1.25-1.25 1.25H9q-1.25 0-1.25-1.25m1.5-3h5.5");
}

</style>
