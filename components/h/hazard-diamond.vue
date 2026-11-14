<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orcf2kb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hazard-diamond" /></template>
<style>
.orcf2kb2l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.475 5.282l4.243 4.243a3.5 3.5 0 0 1 0 4.95l-4.243 4.243a3.5 3.5 0 0 1-4.95 0l-4.243-4.243a3.5 3.5 0 0 1 0-4.95l4.243-4.243a3.5 3.5 0 0 1 4.95 0M12 7v6.25m0 3.5h.01");
}

</style>
