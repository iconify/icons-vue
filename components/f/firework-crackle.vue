<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iha929bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:firework-crackle" /></template>
<style>
.iha929bau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7V2.5m2 5.25l3.25-3M15 10h4.5m-5.25 2.25l3 3m-7.5-3l-3 3M9 10H4.5m5.25-2.25l-3-3M12 21.5V15");
}

</style>
