<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtfpvebsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:antigen" /></template>
<style>
.gtfpvebsl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 12a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0M12 6.25V3m-1.25 0h2.5M12 17.75V21m-1.25 0h2.5m-7-9H3m0-1.25v2.5M17.75 12H21m0-1.25v2.5M16 8l2.25-2.25m-1-1l2 2M8 8L5.75 5.75m-1 1l2-2M16 16l2.25 2.25m1-1l-2 2M8 16l-2.25 2.25m1 1l-2-2");
}

</style>
