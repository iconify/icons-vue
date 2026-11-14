<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrh770b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-ivy" /></template>
<style>
.qrh770b-o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.523 5.195l1.383 2.446a1.75 1.75 0 0 0 1.014.813l2.773.844a1.75 1.75 0 0 1 .924 2.678l-1.882 2.688a1.75 1.75 0 0 1-.595.533l-4.302 2.346a1.75 1.75 0 0 1-1.676 0L6.86 15.197a1.75 1.75 0 0 1-.595-.533l-1.882-2.688a1.75 1.75 0 0 1 .924-2.678l2.773-.844a1.75 1.75 0 0 0 1.014-.813l1.383-2.446a1.75 1.75 0 0 1 3.046 0M12 18v3.5m0-3.5V7.5");
}

</style>
