<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlqdiubzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat-alert" /></template>
<style>
.xlqdiubzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M9.5 4.5V6m5.303.697l-1.06 1.06M17 12h-1.5m-.697 5.303l-1.06-1.06M9.5 19.5V18m-5.303-.697l1.06-1.06M2 12h1.5m.697-5.303l1.06 1.06M20 4v10m0 4.25h.01");
}

</style>
