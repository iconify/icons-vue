<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njo4jsbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:build" /></template>
<style>
.njo4jsbko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.293 4.111l4.596 4.596a1.75 1.75 0 0 1 0 2.475l-.707.707a1.75 1.75 0 0 1-2.475 0l-4.596-4.596a1.75 1.75 0 0 1 0-2.475l.707-.707a1.75 1.75 0 0 1 2.475 0M12.5 9.5L3 19m11.25-3h5A1.75 1.75 0 0 1 21 17.75v2a1.75 1.75 0 0 1-1.75 1.75h-5a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 14.25 16");
}

</style>
