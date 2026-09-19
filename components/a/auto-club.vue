<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="rxt-l306z"/><path class="emmtz_a5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:auto-club" /></template>
<style>
.emmtz_a5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.78 27.963c-2.728 2.804-4.01 5.231-3.203 6.627c.93 1.61 4.435 1.501 9.158.022m15.508-7.572c8.235-5.35 13.459-11.136 12.019-13.63c-1.318-2.282-7.812-1.11-15.61 2.52m-7.064 7.803h-5.442m-1.347 5.32l4.068-16.06l4.068 16.06m-8.178-4.948H8.316m-.7 2.571l3.421-12.559l3.374 12.387m12.966-2.345h-5.442m-.645 2.345l3.366-12.225l3.34 12.13");
}

.rxt-l306z {
  cx: 17.635px;
  cy: 21.304px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.135px;
  ry: 8.311px;
}

</style>
