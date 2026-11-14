<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqx7_vb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:action-call" /></template>
<style>
.fqx7_vb_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10.5h11A3.5 3.5 0 0 1 21 14v3a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17v-3a3.5 3.5 0 0 1 3.5-3.5M3.984 6.713l13.205-2.807a1.75 1.75 0 0 1 2.076 1.348a1.75 1.75 0 0 1-1.348 2.075L4.712 10.136a1.75 1.75 0 0 1-2.076-1.348a1.75 1.75 0 0 1 1.348-2.075m2.69-.572l2.684 3.008m2.207-4.048l2.684 3.008");
}

</style>
