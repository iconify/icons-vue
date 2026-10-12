<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr369rbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:diode" /></template>
<style>
.vr369rbgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12H7.5m8.5 0h5.25M7.5 7.5v9q0 1 .85.48l7.3-4.46q.85-.52 0-1.04l-7.3-4.46q-.85-.52-.85.48m8.5-1v11");
}

</style>
