<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfekwiynr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bronchi" /></template>
<style>
.gfekwiynr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v6m-7.5 12V17l4-4L12 8.5l3.5 4.5l4 4v3.5M8.5 13l1 5.5m6-5.5l-1 5.5");
}

</style>
