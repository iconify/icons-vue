<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m7wxeoook"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:grid-drawing-for-artist" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m7wxeoook {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.194 6.131l.13 35.738M34.887 8.312l.11 30.434M13.395 8.345l.104 30.658M6.972 24.13h34.056M9.175 35.396h29.78M9.105 13.382h29.531m-10.215 6.845a4.281 4.281 0 1 1 .003-.01m4.663 10.942c-1.43 2.31-6.506 3.63-11.339 2.947s-7.596-3.108-6.172-5.42s6.495-3.634 11.33-2.955s7.604 3.104 6.187 5.416");
}

</style>
