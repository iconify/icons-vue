<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk14jwbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atm-mini-statement" /></template>
<style>
.lk14jwbpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14v19L16.75 20l-2.25 1.5L12 20l-2.5 1.5L7.25 20L5 21.5ZM7.75 7h2.5M9 5.75v2.5M12.5 7H16m-8.25 4.5h2.5m2.25 0H16M7.75 16h2.5M9 14.75v2.5M12.5 16H16");
}

</style>
