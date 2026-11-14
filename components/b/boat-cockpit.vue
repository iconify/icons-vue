<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0wa-vble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boat-cockpit" /></template>
<style>
.z0wa-vble {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14h18l-2.5 6H6Zm5.75-6a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M12 3.25V14M7.25 8h9.5");
}

</style>
