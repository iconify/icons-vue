<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddhkcxqnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-edging" /></template>
<style>
.ddhkcxqnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19v-4.5a2.25 2.25 0 0 1 4.5 0V19m0-4.5a2.25 2.25 0 0 1 4.5 0V19m0-4.5a2.25 2.25 0 0 1 4.5 0V19m0-4.5a2.25 2.25 0 0 1 4.5 0V19M2.5 19h19M12 11.75V7m0 1.5c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4M12 7c2.5 0 4-1.5 4-4c-2.5 0-4 1.5-4 4");
}

</style>
