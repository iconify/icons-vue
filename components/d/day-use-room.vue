<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quo5hdczv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:day-use-room" /></template>
<style>
.quo5hdczv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5V3H12v18.5m-9.5 0h19m-6-11.5a2.5 2.5 0 0 1 5 0M12 10h9.5M18 5.5V4m-2.25 2.25L15 5m5.25 1.25L21 5M9.5 13h.01");
}

</style>
