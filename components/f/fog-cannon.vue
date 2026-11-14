<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jj9l2kb9p"/><path class="e3gk6fbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fog-cannon" /></template>
<style>
.e3gk6fbce {
  d: path("m12.443 6.873l.307-.123a.91.91 0 0 1 1.25.846v2.308a.91.91 0 0 1-1.25.846l-.307-.123a1.5 1.5 0 0 1-.943-1.393v-.968a1.5 1.5 0 0 1 .943-1.393M15.5 8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M13.75 20.5a2.5 2.5 0 0 1-.25-5a3 3 0 0 1 5.5-.75a2.75 2.75 0 0 1-.25 5.75Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jj9l2kb9p {
  d: path("M3.5 4za1 1 0 0 1 1 1v7.5a1 1 0 0 1-1 1a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1m2.75 1h3.5a1.75 1.75 0 0 1 1.75 1.75v4a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 6.25 5");
}

</style>
