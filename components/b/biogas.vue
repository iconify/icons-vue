<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhchjzb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:biogas" /></template>
<style>
.jhchjzb1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25v-4a9.25 6 0 0 1 18.5 0v4ZM6 18h12M12 2.75c1.5 1.5 2.25 2.5 2.25 3.75a2.25 2.25 0 0 1-4.5 0c0-1.25.75-2.25 2.25-3.75");
}

</style>
