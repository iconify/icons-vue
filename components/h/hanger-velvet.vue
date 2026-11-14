<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnmmfr95e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hanger-velvet" /></template>
<style>
.rnmmfr95e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9V7a2 2 0 1 0-2-2M2.5 17v-2L5 13.25l.75 1L7 12.5l3.5-3h3l3.5 3l1.25 1.75l.75-1L21.5 15v2Z");
}

</style>
