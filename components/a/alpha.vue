<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odl3q5bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alpha" /></template>
<style>
.odl3q5bbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 5.5c-1.25 5-3.75 12.25-8 12.25c-3 0-4.75-2.5-4.75-5.75s2-5.75 5-5.75c4.25 0 6 6.5 8 10.75c.5 1 1 1.25 1.75 1.25");
}

</style>
