<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2yl1zbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flask-check" /></template>
<style>
.o2yl1zbyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h8m-6.5 0v6L3.75 20q-.5 1 .75 1h9.293m5.883-.005q.806-.054.706-.626m-2.611-5.326L14.5 8.5v-6M7.25 13h9.5m-2 5l2 2L21 15.75");
}

</style>
